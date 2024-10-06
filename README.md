
```markdown
# TikTok Live Monitor

このプロジェクトは、指定したTikTokアカウントのライブ配信を監視し、ライブが始まると自動的にその配信に入るためのPythonスクリプトです。

## 機能

- 指定されたTikTokアカウントのページを定期的にリロードします。
- ライブ配信が始まった場合、自動的にその配信に入ります。
- 手動でのログインが必要ですが、スクリプトがブラウザを自動的に開きます。

## 必要なもの

- Python 3.x
- [Selenium](https://selenium-python.readthedocs.io/) ライブラリ
- Google Chrome
- ChromeDriver

## インストール

1. **Pythonのインストール**
   - Pythonがインストールされていない場合、[公式サイト](https://www.python.org/downloads/)からインストールしてください。

2. **必要なライブラリのインストール**
   ```bash
   pip install selenium
   ```

3. **ChromeDriverのダウンロード**
   - [ChromeDriverのリリースページ](https://chromedriver.chromium.org/downloads)から、使用しているChromeのバージョンに対応するChromeDriverをダウンロードし、適当な場所に配置します。

## 使い方

1. `godpotato live Tracker` スクリプトをエディタで開き、以下の変数を設定します。
   - `chrome_driver_path`: ChromeDriverのパスを指定します。
   - `tiktok_url`: 監視するTikTokアカウントのURLを指定します。

   ```python
   chrome_driver_path = "C:\\path\\to\\chromedriver.exe"  # ここにChromeDriverのパスを設定
   tiktok_url = "https://www.tiktok.com/@godpotato_official"  # 監視するアカウントのURL
   ```

2. コマンドプロンプトまたはターミナルを開き、スクリプトを実行します。
   ```bash
   python godpotatoiveping.py
   ```

3. スクリプトがブラウザを開き、指定したTikTokアカウントのページを監視します。

## 注意事項

- スクリプトを実行する前に、手動でTikTokにログインしてください。ログイン後、スクリプトがライブ配信を監視します。
- ライブ配信が開始されると、自動的にその配信に入ります。

