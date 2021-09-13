Jurus Pertama Android MVVM Data Binding di Java
Data Binding merupakan pintu gerbang Android MVVM , Latihan jurus Data Binding :

1. Update Gradle : di langkah 1 kita update gradle file build.gradle di module app, di dalam android ditambahkan build features{ dataBinding true }
2. Update Layout : di langkah 2 kita update layout Xml di activity / Fragment ke data binding layout, di data binding layout ada tag layout (<layout) dan ada tag data (<data)
3. Layout Expression : di langkah 3 kita update layout Xml dengan layout expression yang sesuai, untuk layout expression yang dicontohkan di youtube ada di dalam tag edit text(<EditText) dan di dalam android:text dan yang layout expression nya yaitu "@viewModel.profileLiveData.username}"
4. Ganti Inflate : di langkah 4 ini kita melakukan ganti cara inflate di fragment/activity, disini ada FragmentTestBending yang merupakan auto generate, jika auto generate gagal maka yang harus dilakukan yaitu clean project jika clean project tidak bisa, maka langkah yang harus dilakukan yaitu rebuild project, jika rebuild project juga tidak bisa maka langkah terakhir yaitu kita close android studio nya lalu kita buka android studio nya lagi, dan untuk sintaks yang ada di fragment yaitu
   binding = DataBindingUtil.inflate(inflater,R.layout.fragment_tes, container, false);
   return binding.getRoot();
   Sedangkan untuk sintaks yang ada di activity seperti ini
   binding = DataBindingUtil.setContentView(activity: this,R.layout.activity_main);  perbedaannya sintaks antara fragment dan activity adalah di bagian return, kalau di fragment menggunakan return kalau di activity tidak menggunakan return
5. User Event : di langkah ke 5 ini kita melakukan handle event dari Xml, di handle event sintaks nya yaitu android:onClick="@{()->viewModel.onBtnUpdateClicked()}, sebelum menggunakan handle event kita harus membuat view model terlebih dahulu dan main activity harus di update dulu
6. Observe : di langkah ke 6 ini akan melakukan observe value dari view model, di sini jika ingin observe value otomatis berubah ada beberapa syarat, syarat 1 adalah live data dan di live data ini ada gradle, syarat ke 2 menggunakan binding.setLifecycleOwner(this); dan jika di syarat ke 2 ini ada view model update akan langsung connect ke xml langsung akan ter update
7. Binding Adapter : di langkah ke 7 ini kita akan kuasai binding adapter
