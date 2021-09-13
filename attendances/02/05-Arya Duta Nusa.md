W01 : 

MVVM intinya adalah databinding yang 
bertujuan untuk membind data ke file xml

MVVM DataBinding jika penggunaannya benar otomatis proses akan jauh lebih 
cepat dan DataBinding ini sebagai pintu gerbang MVVM 

W02 :

MVVM DataBinding jika penggunaannya benar otomatis proses akan jauh lebih 
cepat dan DataBinding ini sebagai pintu gerbang MVVM

Ada 7 step untuk membuat DataBinding
- Update Gradle
	file build.grade di module.app
- Update Layout
	Layout Xml di activity/Fragment ke databinding layout
- Layout Expression
	Sama seperti di blade atau di Laravel
- Ganti Inflate
Biasanya Android Studio akan auto generate sendiri. Jika gagal ada 3 cara yang dapat dilakukan yaitu Clear Project, lalu Clear Project, jika masih tidak bisa Close Android Studio lalu buka lagi dan ini adalah Worse case.
- User Event
- Observe
- Binding Adapter
