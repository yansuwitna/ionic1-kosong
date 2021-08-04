Selesai Download Jalankan Perintah untuk mendownload file node_modules
	ionic init --verbose

Mencoba Ionic
	ionic serve --verbose

Mencoba Ionic Labs
	ionic serve --lab --verbose

Rubah File config.xml
<widget id="===ID===" version="===Versi====" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
    <name>===Tampilan===</name>
    <description>====Deskripsi===</description>
    <author email="====Email Pembuat====" href="===web pembuat====">====Nama Perusahaan====</author>

Menambahkan Platform Android 
	ionic cordova platform add android --verbose

Membuat APK
	ionic cordova build android --verbose

Menjalankan APK ke emulator 
	ionic cordova run android --verbose

Menonaktifkan Status Bar
	cordova plugin add cordova-plugin-hidden-statusbar-overlay

Tampilan Agar Landscape : 
	Edit File config.xml dengan menambahkah 
	<preference name="orientation" value="landscape" />

Merubah Splash dan logo
	ubah foto icon.png dan splash.png pada resources
	kemudian jalankan perintah 
		ionic cordova resources