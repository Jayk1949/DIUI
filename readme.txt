# 安装全局插件 #
# npm scripts 执行删除的插件
sudo npm i -g rimraf

# 初始化package.json
sudo npm install

# 构建方式 #
# 开发模式 半覆盖构建+监听 standard 这个项目
sudo npm run dev standard

# 生产模式 全覆盖构建
sudo npm run build standard


# 对象展开运算无法执行报错的时候，在根目录常见文件 .babelrc #
{
  "presets": ["es2015", "stage-0"]
}
# 保存