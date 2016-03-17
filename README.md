# Capslock2Enter
## これはなに？
Windowsの標準的なJIS配列キーボードのCapsLockキーをEnterキーとして機能させる
レジストリ編集ファイルです。


## 設定方法
1. Capslock2Enter.reg をダウンロードしてダブルクリック
2. PC再起動
3. CapslockがEnterキーになる


## 設定の削除方法
1. Windowsの検索から「regedit.exe」でレジストリエディターを起動する
2. HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layoutを開く
3. Scancode Mapを削除する
