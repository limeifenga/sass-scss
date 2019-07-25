# sass-scss
sass/scss css  不依赖webpack  gulp 工具  在webstrom 中  watch自动编译

第一步：
  sass基于Ruby语言开发而成，因此安装sass前需要安装Ruby。（注:mac下自带Ruby无需在安装Ruby!）
  window  下载Rudy工具到本地  官网下载：https://rubyinstaller.org/downloads/

第二步：
webstrom配置：
在webastorm >settings  >file Watchers 项  
   分别增加  sass  和 scss 的 配置
      在配置时 分别在program  项  选择  本地 D:\Ruby25-x64\bin\sass.bat / D:\Ruby25-x64\bin\scss.bat
      
作用：当修改*sass  / *.scss  文件，  ctrl+s 后  将会自动编译，在对应文件下  编译出*.css 和*.css.map文件



  


