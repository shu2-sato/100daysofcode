# #100DaysOfCode 学習ログ - round1 

私の#100DaysOfCodeチャレンジの学習ログです。2021/03/31開始。

## 学習ログ
### day74 complete 2021/08/05
周期性を変更して時系列データを他のデータと同等にする方法。.resample()
ロケーターを使用して、タイムライン (グラフ上の軸など) のスタイルを改善する方法。matplotlib.dates

移動平均の計算
roll_df_unemployment = df_unemployment[['UE_BENEFITS_WEB_SEARCH','UNRATE']].rolling(window=6).mean()
ax1.plot(df_unemployment.MONTH,roll_df_unemployment.UNRATE,color='purple',linewidth=3,linestyle='--')
ax2.plot(df_unemployment.MONTH,roll_df_unemployment.UE_BENEFITS_WEB_SEARCH,color='skyblue',linewidth=3,marker='o')

### DAY73 complete 2021/07/29
pandas.DataFrame.agg
matplotlib.pyplot.scatter

matplotlibやpandasの関数色々
外部KEYでmerge


### day72 complete 2021/07/27
matplotlib.pyplot.plot

ローリング平均で移動平均ができて、カラムをForで回して１つのグラフに複数の線を弾ける。
便利だ
# 平均すると、6または12の観測値を平均する、ローリング平均
roll_df = reshaped_df.rolling(window=6).mean()

for column in roll_df.columns:
  plt.plot(roll_df.index, roll_df[column],
           linewidth=3, label=roll_df[column].name)


### day71 complete 2021/07/25
pandasとcolabolatry

ipynbと同じdirectoryに置いたファイルであれば、drive mountや認証せずにそのまま使えた。
Pandasで　HTMLのtableをそのまま読み取れる。read_htmlでスクライピングもできる。



### day70 complete 2021/07/25
herokuへの登録
Github使った deploy
gunicornの利用
Postgreへの変更

### day69　complete 2021/07/23
flask-login、WTFFROMのまとめでのBlog更新、
TableのRetation作成
Flasl-gavatarなど
1日のテーマをこなすのに、3日くらい掛かっている。
日数としては、100日を超えているんだけど、やっと70％地点


### day68 complete 2021/07/17
flask-logonの使い方
ログイン状態のチェックやurlのログイン制約をかけれるのは、便利。


###  day67complete  2021/07/14
Flask、WTFForm,Bootstrapを使ったタスクが続いているが、
コースタスクに2、3日かかるタスクが増えてきた。


### day50  2021/06/05
何回かseleniumを使って自動サーチ、登録などbot操作のproject
Cssが整理されてサイトもあれば、意味不明なルールでわかり難いサイトも多い。
bot対策で複雑にしているのだろうか？　リグレッションテストツールでも同じことをしているのだから、
明確なルールで書いていないとテストできないと思うんだけど。。


### day49  2021/06/03
Linkedin でJob search

### day48 2021/05/30
Cookie game

### day46 ## 2021/05/20
soplifyのAPI 
APIドキュメント見てもわからず、難しいかった、3日くらいかかって挫折
APIドキュメント見てわかないのは大変、RPGよりチャレンジングなゲームだ！！


### day39 2021/05/08
day39 :api
API Flight searchAPIの機能使い方がわからず、2日かかった、

関数の引数にClassを渡すとき、objectであることを指定すると、受け取った先のコーディングでのメソッド選択が便利になる。
def send_alert(self,flight : FlightData):
呼ばれるほうのClassとデータobjectは本来関係ない場合は、送るmsg_textだけを引数で渡すほうが自由度が高いので望ましい。

### day 36 2021/05/03
day36: API
stock
news
sms のapiを使ってのproject
海外のapiばかりだけどブラウザの翻訳で割と簡単にできるのは便利

day35 API
smsのapi

### day25 2021/4/20
day 25 50 state 
usのマップの上で州の名前を入力して当たっていたら書き込むゲーム
自国のマップで同じように作成するといい。　データ作るのに手間がかかるかもしれないけど、勉強になる。
学校とかで使うといいかも

### day23 2021/4/18
Day 23 cross car
これも昔のゲームぽい
単純にプログラムの勉強だけじゃなく、ゲームをしながらプログラムを書くので
やる気がでる

### Day22
day22 PONG
昔ながらのピンポンゲーム　懐かしい

### Day21
Udemy/100-days-of-code python
day21 snake game

### day1
Udemy 100-days-of-code pythonを購入したので、100daysOfcode bootcampにチャレンジ
英語のコースだけど日本語字幕あるので、わかりやすい。
熱心な講師でシラバスもしっかりしていて、人気コースとなっている。


 
