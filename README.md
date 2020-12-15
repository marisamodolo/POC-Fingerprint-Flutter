### POC Fingerprint Flutter

Foi utilizado o pacote [local_auth](https://pub.dev/packages/local_auth) para fazer a validação biométrica.

Foi necessário adicionar a permissão de `USE_FINGERPRINT` e `USE_BIOMETRIC` no `AndroidManifest.xml`
```
<manifest xmlns:android="http://schemas.android.com/apk/res/android" package="com.example.app">
  <uses-permission android:name="android.permission.USE_FINGERPRINT"/>
  <uses-permission android:name="android.permission.USE_BIOMETRIC"/>
<manifest>
```
