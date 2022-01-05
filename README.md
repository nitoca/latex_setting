# latex_setting
setting.jsonとlatexmkrcはwin,mac共通で使用できる。  
wslでbuildすると文字コードの関係か.flsと.synctex.gzファイルが消えないので、別途rm_tex.shという名前のshell scriptを用意した。
また、私の環境ではrm_tex.shの実行するためのaliasを.bashrcに書きこんだ。（私の場合、rmtexで「out/」以下のファイルが消えるようになっている。）