+++
date = '2024-11-10T02:31:50+08:00'
draft = true
title = 'Q'

+++

hugo is the main command, used to build your Hugo site.

Hugo is a Fast and Flexible Static Site Generator
built with love by spf13 and friends in Go.

Complete documentation is available at https://gohugo.io/.

Usage:
  hugo [flags]
  hugo [command]

Available Commands:
  build       Build your site
  completion  Generate the autocompletion script for the specified shell
  config      Display site configuration
  convert     Convert front matter to another format
  env         Display version and environment info
  gen         Generate documentation and syntax highlighting styles
  help        Help about any command
  import      Import a site from another system
  list        List content
  mod         Manage modules
  new         Create new content
  server      Start the embedded web server
  version     Display version

Flags:
  -b, --baseURL string             hostname (and path) to the root, e.g. https://spf13.com/
  -D, --buildDrafts                include content marked as draft
  -E, --buildExpired               include expired content
  -F, --buildFuture                include content with publishdate in the future
      --cacheDir string            filesystem path to cache directory
      --cleanDestinationDir        remove files from destination not found in static directories
      --clock string               set the clock used by Hugo, e.g. --clock 2021-11-06T22:30:00.00+09:00
      --config string              config file (default is hugo.yaml|json|toml)
      --configDir string           config dir (default "config")
  -c, --contentDir string          filesystem path to content directory
      --debug                      debug output
  -d, --destination string         filesystem path to write files to
      --disableKinds strings       disable different kind of pages (home, RSS etc.)
      --enableGitInfo              add Git revision, date, author, and CODEOWNERS info to the pages
  -e, --environment string         build environment
      --forceSyncStatic            copy all files when static is changed.
      --gc                         enable to run some cleanup tasks (remove unused cache files) after the build
  -h, --help                       help for hugo
      --ignoreCache                ignores the cache directory
      --ignoreVendorPaths string   ignores any _vendor for module paths matching the given Glob pattern
  -l, --layoutDir string           filesystem path to layout directory
      --logLevel string            log level (debug|info|warn|error)
      --minify                     minify any supported output format (HTML, XML etc.)
      --noBuildLock                don't create .hugo_build.lock file
      --noChmod                    don't sync permission mode of files
      --noTimes                    don't sync modification time of files
      --panicOnWarning             panic on first WARNING log
      --poll string                set this to a poll interval, e.g --poll 700ms, to use a poll based approach to watch for file system changes
      --printI18nWarnings          print missing translations
      --printMemoryUsage           print memory usage to screen at intervals
      --printPathWarnings          print warnings on duplicate target paths etc.
      --printUnusedTemplates       print warnings on unused templates.
      --quiet                      build in quiet mode
      --renderSegments strings     named segments to render (configured in the segments config)
  -M, --renderToMemory             render to memory (mostly useful when running the server)
  -s, --source string              filesystem path to read files relative from
      --templateMetrics            display metrics about template executions
      --templateMetricsHints       calculate some improvement hints when combined with --templateMetrics
  -t, --theme strings              themes to use (located in /themes/THEMENAME/)
      --themesDir string           filesystem path to themes directory
      --trace file                 write trace to file (not useful in general)
  -v, --verbose                    verbose output
  -w, --watch                      watch filesystem for changes and recreate as needed



<iframe _ngcontent-ng-c4231339516="" width="100%" frameborder="0" marginwidth="0" marginheight="0" height="0px" src="https://dict.eudic.net/dicts/MiniDictSearch2?word=hugo%20is%20the%20main%20command%2C%20used%20to%20build%20your%20Hugo%20site.%0A%0AHugo%20is%20a%20Fast%20and%20Flexible%20Static%20Site%20Generator%20built%20with%20love%20by%20spf13%20and%20friends%20in%20Go.%0A%0AComplete%20documentation%20is%20available%20at%20https%3A%2F%2Fgohugo.io%2F.%0A%0AUsage%3A%20hugo%20%5Bflags%5D%20hugo%20%5Bcommand%5D%0A%0AAvailable%20Commands%3A%20build%20Build%20your%20site%20completion%20Generate%20the%20autocompletion%20script%20for%20the%20specified%20shell%20config%20Display%20site%20configuration%20convert%20Convert%20front%20matter%20to%20another%20format%20env%20Display%20version%20and%20environment%20info%20gen%20Generate%20documentation%20and%20syntax%20highlighting%20styles%20help%20Help%20about%20any%20command%20import%20Import%20a%20site%20from%20another%20system%20list%20List%20content%20mod%20Manage%20modules%20new%20Create%20new%20content%20server%20Start%20the%20embedded%20web%20server%20version%20Display%20version%0A%0AFlags%3A%20-b%2C%20%E2%80%93baseURL%20string%20hostname%20(and%20path)%20to%20the%20root%2C%20e.g.%20https%3A%2F%2Fspf13.com%2F%20-D%2C%20%E2%80%93buildDrafts%20include%20content%20marked%20as%20draft%20-E%2C%20%E2%80%93buildExpired%20include%20expired%20content%20-F%2C%20%E2%80%93buildFuture%20include%20content%20with%20publishdate%20in%20the%20future%20%E2%80%93cacheDir%20string%20filesystem%20path%20to%20cache%20directory%20%E2%80%93cleanDestinationDir%20remove%20files%20from%20destination%20not%20found%20in%20static%20directories%20%E2%80%93clock%20string%20set%20the%20clock%20used%20by%20Hugo%2C%20e.g.%20%E2%80%93clock%202021-11-06T22%3A30%3A00.00%2B09%3A00%20%E2%80%93config%20string%20config%20file%20(default%20is%20hugo.yaml%7Cjson%7Ctoml)%20%E2%80%93configDir%20string%20config%20dir%20(default%20%E2%80%9Cconfig%E2%80%9D)%20-c%2C%20%E2%80%93contentDir%20string%20filesystem%20path%20to%20content%20directory%20%E2%80%93debug%20debug%20output%20-d%2C%20%E2%80%93destination%20string%20filesystem%20path%20to%20write%20files%20to%20%E2%80%93disableKinds%20strings%20disable%20different%20kind%20of%20pages%20(home%2C%20RSS%20etc.)%20%E2%80%93enableGitInfo%20add%20Git%20revision%2C%20date%2C%20author%2C%20and%20CODEOWNERS%20info%20to%20the%20pages%20-e%2C%20%E2%80%93environment%20string%20build%20environment%20%E2%80%93forceSyncStatic%20copy%20all%20files%20when%20static%20is%20changed.%20%E2%80%93gc%20enable%20to%20run%20some%20cleanup%20tasks%20(remove%20unused%20cache%20files)%20after%20the%20build%20-h%2C%20%E2%80%93help%20help%20for%20hugo%20%E2%80%93ignoreCache%20ignores%20the%20cache%20directory%20%E2%80%93ignoreVendorPaths%20string%20ignores%20any%20_vendor%20for%20module%20paths%20matching%20the%20given%20Glob%20pattern%20-l%2C%20%E2%80%93layoutDir%20string%20filesystem%20path%20to%20layout%20directory%20%E2%80%93logLevel%20string%20log%20level%20(debug%7Cinfo%7Cwarn%7Cerror)%20%E2%80%93minify%20minify%20any%20supported%20output%20format%20(HTML%2C%20XML%20etc.)%20%E2%80%93noBuildLock%20don%E2%80%99t%20create%20.hugo_build.lock%20file%20%E2%80%93noChmod%20don%E2%80%99t%20sync%20permission%20mode%20of%20files%20%E2%80%93noTimes%20don%E2%80%99t%20sync%20modification%20time%20of%20files%20%E2%80%93panicOnWarning%20panic%20on%20first%20WARNING%20log%20%E2%80%93poll%20string%20set%20this%20to%20a%20poll%20interval%2C%20e.g%20%E2%80%93poll%20700ms%2C%20to%20use%20a%20poll%20based%20approach%20to%20watch%20for%20file%20system%20changes%20%E2%80%93printI18nWarnings%20print%20missing%20translations%20%E2%80%93printMemoryUsage%20print%20memory%20usage%20to%20screen%20at%20intervals%20%E2%80%93printPathWarnings%20print%20warnings%20on%20duplicate%20target%20paths%20etc.%20%E2%80%93printUnusedTemplates%20print%20warnings%20on%20unused%20templates.%20%E2%80%93quiet%20build%20in%20quiet%20mode%20%E2%80%93renderSegments%20strings%20named%20segments%20to%20render%20(configured%20in%20the%20segments%20config)%20-M%2C%20%E2%80%93renderToMemory%20render%20to%20memory%20(mostly%20useful%20when%20running%20the%20server)%20-s%2C%20%E2%80%93source%20string%20filesystem%20path%20to%20read%20files%20relative%20from%20%E2%80%93templateMetrics%20display%20metrics%20about%20template%20executions%20%E2%80%93templateMetricsHints%20calculate%20some%20improvement%20hints%20when%20combined%20with%20%E2%80%93templateMetrics%20-t%2C%20%E2%80%93theme%20strings%20themes%20to%20use%20(located%20in%20%2Fthemes%2FTHEMENAME%2F)%20%E2%80%93themesDir%20string%20filesystem%20path%20to%20themes%20directory%20%E2%80%93trace%20file%20write%20trace%20to%20file%20(not%20useful%20in%20general)%20-v%2C%20%E2%80%93verbose%20verbose%20output%20-w%2C%20%E2%80%93watch%20watch%20filesystem%20for%20changes%20and%20recreate%20as%20needed"></iframe>

微软翻译

hugo 是主要命令，用于构建您的 Hugo 站点。 Hugo 是一个快速灵活的静态站点生成器，由 spf13 和 Go 中的朋友用爱构建。 https://gohugo.io/ 上提供了完整的文档。 用法： hugo [flags] hugo [command] 可用命令： build 构建站点补全 为指定的 shell 配置 生成自动补全脚本 显示站点配置 转换 将前言转换为其他格式 env 显示版本和环境信息 gen 生成文档和语法高亮样式 帮助 关于任何命令导入的帮助 从另一个系统列表导入站点 列出内容模组 管理模块 新 创建新的内容服务器 启动嵌入式 Web 服务器版本 显示版本 标志： -b， –baseURL 字符串 根目录的主机名（和路径），例如 https://spf13.com/ -D， –buildDrafts 包含标记为草稿的内容 -E， –buildExpired 包含过期的内容 -F， –buildFuture 包含发布日期在未来的内容 –cacheDir 字符串缓存目录的文件系统路径 –cleanDestinationDir 从静态目录中找不到的目标中删除文件 –clock string 设置 Hugo 使用的时钟， 例如 –clock 2021-11-06T22：30：00.00+09：00 –config 字符串配置文件（默认为 hugo.yaml|json|toml） –configDir 字符串配置目录（默认为 “config”） -c， –contentDir 字符串内容目录的文件系统路径 –debug debug output -d， –destination 字符串将文件写入的文件系统路径 –disableKinds 字符串禁用不同类型的页面（主页、RSS 等） –enableGitInfo 添加 Git 修订、日期、作者、 和 CODEOWNERS 信息添加到页面 -e， –environment 字符串构建环境 –forceSyncStatic 更改 static 时复制所有文件。–gc enable 在构建后运行一些清理任务（删除未使用的缓存文件） -h， –hugo 的帮助 –ignoreCache 忽略缓存目录 –ignoreVendorPaths 字符串忽略与给定 Glob 模式匹配的模块路径的任何_vendor -l， –layoutDir 字符串布局目录的文件系统路径 –logLevel 字符串日志级别 （debug|info|warn|error） –minify 缩小任何支持的输出格式（HTML， XML 等）–noBuildLock 不创建 .hugo_build.lock 文件 –noChmod 不同步文件的权限模式 –noTimes 不同步文件的修改时间 –panicOnWarning 在第一个警告日志上出现紧急情况 –poll 字符串将此设置为轮询间隔，例如 –poll 700ms，以使用基于轮询的方法监视文件系统更改 –printI18nWarnings 打印缺少的翻译 –printMemoryUsage 每隔一段时间将内存使用情况打印到屏幕 –printPathWarnings 在重复的目标路径上打印警告等 –printUnusedTemplates在未使用的模板上打印警告。–安静模式下的构建 –renderSegments 字符串指定要渲染的片段（在片段配置中配置） -M， –renderToMemory 渲染到内存（在运行服务器时非常有用） -s， –源字符串 读取文件的路径 相对于 –templateMetrics 显示有关模板执行的指标 –templateMetricsHints 与 –templateMetrics -t， –theme strings 结合使用时计算一些改进提示（位于 /themes/THEMENAME/） –themesDir 字符串文件系统路径到主题目录 –trace file write trace to file （一般没有用） -v， –verbose verbose output -w， –watch watch filesystem 是否有更改并根据需要重新创建
