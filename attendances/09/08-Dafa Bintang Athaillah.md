# Flutter API

### Link repo
link repo: https://github.com/Dafaathaillah/flutter-api.git

### Resume Praktikum 1 Nov
pada pertemuan 1 november bersama dengan saudara farid maulana yang kerap di sapa dengan farlan,
saudara farlan melanjutkan project flutter-api sebelumnya pada project ini saudara farlan menjelaskan
bagaimana cara menggunakan auth sanctum dan sbeelumnya saudara farlan juga mendemokan bagaimana cara menggunakan
php artisan tinker untuk mengisert data.
pada praktikum kali ini saudara farlan juga mengajarkan bagaimana cara membuat register, login, dan juga logot
yang mana nantinya ketika kita login akan mendapatkan sebuh token dan juga saudara farlan mengajarkan bagaimana 
cara menampilkan data berdasarkan user_id/user yang sedang login menggunakan "booted"
berikut contoh penggunaan "booted" pada model transaction: 

protected static function booted()
    {
        static::addGlobalScope('by_user', function (Builder $builder) {
            $builder->where('user_id', auth()->id());
        });
    }
    
selain menggunakan booted sebelumnya saudara farlan memberi arahan untuk menambahkan relasi pada model user 
agar berelasi terhadap model category dan tansaction dengan menggunakan hasMany berikut contoh penggunaannya: 

  public function transactions()
    {
        return $this->hasMany(Transaction::class);
    }
berikut untuk contoh penggunaan auth sanctum pada auth controller:

## Register:

 public function register(Request $request){
        $request->validate([
            'name' => 'required|string|max:255',
            'email' => 'required|email|string|max:255|unique:users',
            'password' => ['required', 'confirmed', Password::defaults()],
            'device_name' => 'required',
        ]);
    
        $user = User::create([
            'name' => $request->name,
            'email' => $request->email,
            'password' => Hash::make($request->password),
        ]);
    
        return $user->createToken($request->device_name)->plainTextToken;
    }
    
## Login:

public function login(Request $request){
        $request->validate([
            'email' => 'required|email',
            'password' => 'required',
            'device_name' => 'required',
        ]);
    
        $user = User::where('email', $request->email)->first();
    
        if (! $user || ! Hash::check($request->password, $user->password)) {
            throw ValidationException::withMessages([
                'email' => ['The provided credentials are incorrect.'],
            ]);
        }
    
        return $user->createToken($request->device_name)->plainTextToken;
    }
    
## Logout:

public function logout(Request $request){
        $user = User::where('email', $request->email)->first();

        if ($user) {
            $user->tokens()->delete();
        }
        return 'Anda berhasil Logout';
    }

berikut resume pada pertemuan 1 nov bersama saudara farlan | Terimakasih
---
