
# WebView ile Flutter Web görünümlü mobil uygulama

Bu uygulama, Flutter kullanarak web sayfalarını görüntülemek için WebView widget'ını kullanır.

## Kurulum

1. **Flutter SDK Kurulumu**: Eğer bilgisayarınızda Flutter SDK yüklü değilse, [Flutter resmi web sitesinden](https://flutter.dev/docs/get-started/install) SDK'yı indirip kurun.
  
2. **Proje Oluşturma**: Bir Flutter projesi oluşturmak için terminal veya komut istemcisinde şu komutu çalıştırın:
    ```
    flutter create my_webview_app
    ```

3. **WebView Eklentisi Eklenmesi**: `webview_flutter` eklentisini `pubspec.yaml` dosyasına ekleyin ve projeyi yeniden oluşturun:
    ```yaml
    dependencies:
      flutter:
        sdk: flutter
      webview_flutter: ^2.0.13 # veya en son sürüm
    ```

## Kullanım

1. **Ana Widget**: `MyApp` adlı ana widget, `MaterialApp` içerisinde `Scaffold` kullanır. Scaffold'ın `body` kısmında WebView yer alır.

2. **WebView**: WebView widget'ı, web sayfasını görüntülemek için kullanılır. `initialUrl` parametresiyle başlangıç URL'si belirtilir ve `javascriptMode` ile JavaScript'in etkinleştirilip devre dışı bırakılabilir.

## Çalıştırma

Proje dizininde terminal veya komut istemcisinde şu komutu çalıştırarak uygulamayı başlatabilirsiniz:
```
flutter run
```

Bu komut, Flutter SDK'yı kullanarak projeyi derleyecek ve başlatılacak ve ardından uygulama bir simülatörde veya gerçek cihazda çalışacaktır.

