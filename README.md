# one-click Line Notify

### one-click 自動佈署一個 Line Notify Web-API 到Heroku的專案按鈕

- 可以按以下的按鈕進行自動佈署本App
- one-click button to auto deploy this demo

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


### 說明如下
- 如下，要加入這一段，就可以產生按鈕，可以參考[這邊](https://devcenter.heroku.com/articles/heroku-button)


`[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)`


- 這一個App有幾個元素，是一個App最基本的三個檔案：
    - app.py: 主程式
    - Procfile: App類型，如何啟動
    - requirements.txt: 需要的套件
    
- 另外，在你的repo上根目錄下放一個 app.json 檔，格式如下，這邊我只放入了三個必要的項目(Heroku建議要有這三項)：
<code><pre>
{
    "name": "line notify demo",
    "description": "a basic line notify web-api at heroku",
    "repository": "https://github.com/maloyang/one-click-line-notify"
}
</pre></code>

- 這邊要注意到你的「description有字數的限制」! 好像是40bytes，之前我一直失敗就是沒注意到不可寫太多說明…


### one-click教學 請參考[這邊](https://github.com/maloyang/one-click-line-echo)。
