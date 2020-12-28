PHP函数速查表 PHP函数大全 

[数组](#数组)

[字符串](#字符串)

[多字节字符串](#多字节字符串)

[变量处理](#变量处理)

[文件系统](#文件系统)

[目录处理](#目录处理)

[数学](#数学)

[类和对象](#类和对象)

[字符类型检测Ctype](#字符类型检测)

[日期和时间](#日期和时间)

[CURL](#CURL)

[过滤器Filter](#过滤器)

[函数处理](#函数处理)

[正则处理PCRE](#正则处理)

[网络Network](#网络)

[程序执行](#程序执行)

[PHP选项和信息](#PHP选项和信息)

[错误处理](#错误处理)

[输出缓冲控制](#输出缓冲控制)

[密码散列算法](#密码散列算法)

[会话Session](#Session)

[CSPRNG伪随机数产生器](#CSPRNG)

[JSON](#JSON)

[Stream](#Stream)

[SPL](#SPL)

[BCMath](#BCMath)

[杂项](#杂项)

[Hash](#hash)

[PDO](#PDO)

[MySQLi](#MySQLi)

[文件信息Fileinfo](#Fileinfo)

[字符集转换iconv](#iconv)

[图像处理GD](#GD)

[Exif可交换图像信息](#Exif)

[URLs](#URLs)

[套接字Sockets](#Sockets)

[XML解析器](#XMLParser)

[OPcache](#OPcache)

[APC用户缓存](#APCU)

[外部函数接口](#FFI)

[MongoDB](#MongoDB)

[Redis](#Redis)

[PHP中文站](https://www.p2hp.com) \--提供  

数组
--

  

*   [array\_change\_key\_case](http://php.p2hp.com/manual/zh/function.array-change-key-case.php) - 更改数组中所有键的大小写
*   [array\_chunk](http://php.p2hp.com/manual/zh/function.array-chunk.php) - 将数组拆分为块
*   [array\_column](http://php.p2hp.com/manual/zh/function.array-column.php) - 返回输入数组中单个列的值
*   [array\_combine](http://php.p2hp.com/manual/zh/function.array-combine.php) - 通过使用一个数组作为键而另一个数组作为其值来创建数组
*   [array\_count\_values](http://php.p2hp.com/manual/zh/function.array-count-values.php) - 计算数组的所有值
*   [array\_diff\_assoc](http://php.p2hp.com/manual/zh/function.array-diff-assoc.php) - 使用附加索引检查计算数组的差异
*   [array\_diff\_key](http://php.p2hp.com/manual/zh/function.array-diff-key.php) - 使用密钥计算数组的差异以进行比较
*   [array\_diff\_uassoc](http://php.p2hp.com/manual/zh/function.array-diff-uassoc.php) - 使用用户提供的回调函数执行附加索引检查来计算数组的差异
*   [array\_diff\_ukey](http://php.p2hp.com/manual/zh/function.array-diff-ukey.php) - 使用键上的回调函数计算数组的差异以进行比较
*   [array\_diff](http://php.p2hp.com/manual/zh/function.array-diff.php) - 计算数组的差异
*   [array\_fill\_keys](http://php.p2hp.com/manual/zh/function.array-fill-keys.php) - 使用值填充数组，指定键
*   [array\_fill](http://php.p2hp.com/manual/zh/function.array-fill.php) - 使用值填充数组
*   [array\_filter](http://php.p2hp.com/manual/zh/function.array-filter.php) - 使用回调函数过滤数组的元素
*   [array\_flip](http://php.p2hp.com/manual/zh/function.array-flip.php) - 在数组中交换所有键及其关联值
*   [array\_intersect\_assoc](http://php.p2hp.com/manual/zh/function.array-intersect-assoc.php) - 使用附加索引检查计算数组的交集
*   [array\_intersect\_key](http://php.p2hp.com/manual/zh/function.array-intersect-key.php) - 使用键进行比较来计算数组的交集
*   [array\_intersect\_uassoc](http://php.p2hp.com/manual/zh/function.array-intersect-uassoc.php) - 使用附加索引检查计算数组的交集，通过回调函数比较索引
*   [array\_intersect\_ukey](http://php.p2hp.com/manual/zh/function.array-intersect-ukey.php) - 使用键上的回调函数计算数组的交集以进行比较
*   [array\_intersect](http://php.p2hp.com/manual/zh/function.array-intersect.php) - 计算数组的交集
*   [array\_key\_exists](http://php.p2hp.com/manual/zh/function.array-key-exists.php) - 检查数组中是否存在给定的键或索引
*   [array\_key\_first](http://php.p2hp.com/manual/zh/function.array-key-first.php) - 获取数组的第一个键
*   [array\_key\_last](http://php.p2hp.com/manual/zh/function.array-key-last.php) - 获取数组的最后一个键
*   [array\_keys](http://php.p2hp.com/manual/zh/function.array-keys.php) - 返回数组的所有键或键的子集
*   [array\_map](http://php.p2hp.com/manual/zh/function.array-map.php) - 将回调应用于给定数组的元素
*   [array\_merge\_recursive](http://php.p2hp.com/manual/zh/function.array-merge-recursive.php) - 递归地合并一个或多个数组
*   [array\_merge](http://php.p2hp.com/manual/zh/function.array-merge.php) - 合并一个或多个数组
*   [array\_multisort](http://php.p2hp.com/manual/zh/function.array-multisort.php) - 对多维或多维数组进行排序
*   [array\_pad](http://php.p2hp.com/manual/zh/function.array-pad.php) - 使用值将数组填充到指定的长度
*   [array\_pop](http://php.p2hp.com/manual/zh/function.array-pop.php) - 从数组末尾弹出元素
*   [array\_product](http://php.p2hp.com/manual/zh/function.array-product.php) - 计算数组中值的乘积
*   [array\_push](http://php.p2hp.com/manual/zh/function.array-push.php) - 将一个或多个元素推送到数组的末尾
*   [array\_rand](http://php.p2hp.com/manual/zh/function.array-rand.php) - 从数组中选择一个或多个随机密钥
*   [array\_reduce](http://php.p2hp.com/manual/zh/function.array-reduce.php) - 使用回调函数迭代地将数组减少为单个值
*   [array\_replace\_recursive](http://php.p2hp.com/manual/zh/function.array-replace-recursive.php) - 以递归方式将传递数组中的元素替换为第一个数组
*   [array\_replace](http://php.p2hp.com/manual/zh/function.array-replace.php) - 将传递的数组中的元素替换为第一个数组
*   [array\_reverse](http://php.p2hp.com/manual/zh/function.array-reverse.php) - 以相反的顺序返回包含元素的数组
*   [array\_search](http://php.p2hp.com/manual/zh/function.array-search.php) - 在数组中搜索给定值，如果成功则返回第一个相应的键
*   [array\_shift](http://php.p2hp.com/manual/zh/function.array-shift.php) - 从数组的开头移出一个元素
*   [array\_slice](http://php.p2hp.com/manual/zh/function.array-slice.php) - 提取数组的切片
*   [array\_splice](http://php.p2hp.com/manual/zh/function.array-splice.php) - 删除数组的一部分并将其替换为其他内容
*   [array\_sum](http://php.p2hp.com/manual/zh/function.array-sum.php) - 计算数组中值的总和
*   [array\_udiff\_assoc](http://php.p2hp.com/manual/zh/function.array-udiff-assoc.php) - 使用附加索引检查计算数组的差异，通过回调函数比较数据
*   [array\_udiff\_uassoc](http://php.p2hp.com/manual/zh/function.array-udiff-uassoc.php) - 使用附加索引检查计算数组的差异，通过回调函数比较数据和索引
*   [array\_udiff](http://php.p2hp.com/manual/zh/function.array-udiff.php) - 通过使用回调函数进行数据比较来计算数组的差异
*   [array\_uintersect\_assoc](http://php.p2hp.com/manual/zh/function.array-uintersect-assoc.php) - 使用附加索引检查计算数组的交集，通过回调函数比较数据
*   [array\_uintersect\_uassoc](http://php.p2hp.com/manual/zh/function.array-uintersect-uassoc.php) - 使用附加索引检查计算数组的交集，通过单独的回调函数比较数据和索引
*   [array\_uintersect](http://php.p2hp.com/manual/zh/function.array-uintersect.php) - 计算数组的交集，通过回调函数比较数据
*   [array\_unique](http://php.p2hp.com/manual/zh/function.array-unique.php) - 从数组中删除重复值
*   [array\_unshift](http://php.p2hp.com/manual/zh/function.array-unshift.php) - 将一个或多个元素添加到数组的开头
*   [array\_values](http://php.p2hp.com/manual/zh/function.array-values.php) - 返回数组的所有值
*   [array\_walk\_recursive](http://php.p2hp.com/manual/zh/function.array-walk-recursive.php) - 递归地将用户函数应用于数组的每个成员
*   [array\_walk](http://php.p2hp.com/manual/zh/function.array-walk.php) - 将用户提供的函数应用于数组的每个成员
*   [array](http://php.p2hp.com/manual/zh/function.array.php) - 创建一个数组
*   [arsort](http://php.p2hp.com/manual/zh/function.arsort.php) - 按相反顺序对数组进行排序并保持索引关联
*   [asort](http://php.p2hp.com/manual/zh/function.asort.php) - 对数组进行排序并维护索引关联
*   [compact](http://php.p2hp.com/manual/zh/function.compact.php) - 创建包含变量及其值的数组
*   [count](http://php.p2hp.com/manual/zh/function.count.php) - 计算数组中的所有元素或对象中的某些元素
*   [current](http://php.p2hp.com/manual/zh/function.current.php) - 返回数组中的当前元素
*   [each](http://php.p2hp.com/manual/zh/function.each.php) - 从数组中返回当前键和值对并使数组光标前进
*   [end](http://php.p2hp.com/manual/zh/function.end.php) - 将数组的内部指针设置为其最后一个元素
*   [extract](http://php.p2hp.com/manual/zh/function.extract.php) - 将变量从数组导入当前符号表
*   [in\_array](http://php.p2hp.com/manual/zh/function.in-array.php) - 检查数组中是否存在值
*   [key\_exists](http://php.p2hp.com/manual/zh/function.key-exists.php) - array\_key\_exists的别名
*   [key](http://php.p2hp.com/manual/zh/function.key.php) - 从数组中获取密钥
*   [krsort](http://php.p2hp.com/manual/zh/function.krsort.php) - 按相反顺序按键排序数组
*   [ksort](http://php.p2hp.com/manual/zh/function.ksort.php) - 按键排序数组
*   [list](http://php.p2hp.com/manual/zh/function.list.php) - 将变量分配为数组
*   [natcasesort](http://php.p2hp.com/manual/zh/function.natcasesort.php) - 使用不区分大小写的“自然顺序”算法对数组进行排序
*   [natsort](http://php.p2hp.com/manual/zh/function.natsort.php) - 使用“自然顺序”算法对数组进行排序
*   [next](http://php.p2hp.com/manual/zh/function.next.php) - 前进阵列的内部指针
*   [pos](http://php.p2hp.com/manual/zh/function.pos.php) - current的别名
*   [prev](http://php.p2hp.com/manual/zh/function.prev.php) - 倒回内部数组指针
*   [range](http://php.p2hp.com/manual/zh/function.range.php) - 创建包含一系列元素的数组
*   [reset](http://php.p2hp.com/manual/zh/function.reset.php) - 将数组的内部指针设置为其第一个元素
*   [rsort](http://php.p2hp.com/manual/zh/function.rsort.php) - 按相反顺序对数组进行排序
*   [shuffle](http://php.p2hp.com/manual/zh/function.shuffle.php) - 随机播放阵列
*   [sizeof](http://php.p2hp.com/manual/zh/function.sizeof.php) - count别名
*   [sort](http://php.p2hp.com/manual/zh/function.sort.php) - 对数组进行排序
*   [uasort](http://php.p2hp.com/manual/zh/function.uasort.php) - 使用用户定义的比较函数对数组进行排序并维护索引关联
*   [uksort](http://php.p2hp.com/manual/zh/function.uksort.php) - 使用用户定义的比较函数按键对数组进行排序
*   [usort](http://php.p2hp.com/manual/zh/function.usort.php) - 使用用户定义的比较函数按值对数组进行排序

  

字符串
---

  

*   [addcslashes](http://php.p2hp.com/manual/zh/function.addcslashes.php) - 使用C样式的斜杠引用字符串
*   [addslashes](http://php.p2hp.com/manual/zh/function.addslashes.php) - 用斜杠引用字符串
*   [bin2hex](http://php.p2hp.com/manual/zh/function.bin2hex.php) - 将二进制数据转换为十六进制表示
*   [chop](http://php.p2hp.com/manual/zh/function.chop.php) - rtrim的别名
*   [chr](http://php.p2hp.com/manual/zh/function.chr.php) - 从数字生成单字节字符串
*   [chunk\_split](http://php.p2hp.com/manual/zh/function.chunk-split.php) - 将字符串拆分为较小的块
*   [convert\_cyr\_string](http://php.p2hp.com/manual/zh/function.convert-cyr-string.php) - 从一个西里尔字符集转换为另一个字符集
*   [convert\_uudecode](http://php.p2hp.com/manual/zh/function.convert-uudecode.php) - 解码一个uuencoded字符串
*   [convert\_uuencode](http://php.p2hp.com/manual/zh/function.convert-uuencode.php) - Uuencode一个字符串
*   [count\_chars](http://php.p2hp.com/manual/zh/function.count-chars.php) - 返回有关字符串中使用的字符的信息
*   [crc32](http://php.p2hp.com/manual/zh/function.crc32.php) - 计算字符串的crc32多项式
*   [crypt](http://php.p2hp.com/manual/zh/function.crypt.php) - 单向字符串哈希
*   [echo](http://php.p2hp.com/manual/zh/function.echo.php) - 输出一个或多个字符串
*   [explode](http://php.p2hp.com/manual/zh/function.explode.php) - 按字符串拆分字符串
*   [fprintf](http://php.p2hp.com/manual/zh/function.fprintf.php) - 将格式化的字符串写入流
*   [get\_html\_translation\_table](http://php.p2hp.com/manual/zh/function.get-html-translation-table.php) - 返回htmlspecialchars和htmlentities使用的转换表
*   [hebrev](http://php.p2hp.com/manual/zh/function.hebrev.php) - 将逻辑希伯来文本转换为可视文本
*   [hebrevc](http://php.p2hp.com/manual/zh/function.hebrevc.php) - 使用换行符转换逻辑希伯来语文本到可视文本
*   [hex2bin](http://php.p2hp.com/manual/zh/function.hex2bin.php) - 对十六进制编码的二进制字符串进行解码
*   [html\_entity\_decode](http://php.p2hp.com/manual/zh/function.html-entity-decode.php) - 将HTML实体转换为相应的字符
*   [htmlentities](http://php.p2hp.com/manual/zh/function.htmlentities.php) - 将所有适用的字符转换为HTML实体
*   [htmlspecialchars\_decode](http://php.p2hp.com/manual/zh/function.htmlspecialchars-decode.php) - 将特殊HTML实体转换回字符
*   [htmlspecialchars](http://php.p2hp.com/manual/zh/function.htmlspecialchars.php) - 将特殊字符转换为HTML实体
*   [implode](http://php.p2hp.com/manual/zh/function.implode.php) - 使用字符串连接数组元素
*   [join](http://php.p2hp.com/manual/zh/function.join.php) - implode的别名
*   [lcfirst](http://php.p2hp.com/manual/zh/function.lcfirst.php) - 将字符串的第一个字符设为小写
*   [levenshtein](http://php.p2hp.com/manual/zh/function.levenshtein.php) - 计算两个弦之间的Levenshtein距离
*   [localeconv](http://php.p2hp.com/manual/zh/function.localeconv.php) - 获取数字格式信息
*   [ltrim](http://php.p2hp.com/manual/zh/function.ltrim.php) - 从字符串的开头删除空格(或其他字符)
*   [md5\_file](http://php.p2hp.com/manual/zh/function.md5-file.php) - 计算给定文件的md5哈希值
*   [md5](http://php.p2hp.com/manual/zh/function.md5.php) - 计算字符串的md5哈希值
*   [metaphone](http://php.p2hp.com/manual/zh/function.metaphone.php) - 计算字符串的metaphone密钥
*   [money\_format](http://php.p2hp.com/manual/zh/function.money-format.php) - 将数字格式化为货币字符串
*   [nl\_langinfo](http://php.p2hp.com/manual/zh/function.nl-langinfo.php) - 查询语言和区域设置信息
*   [nl2br](http://php.p2hp.com/manual/zh/function.nl2br.php) - 在字符串中的所有换行符之前插入HTML换行符
*   [number\_format](http://php.p2hp.com/manual/zh/function.number-format.php) - 格式化分组为千的数字
*   [ord](http://php.p2hp.com/manual/zh/function.ord.php) - 将字符串的第一个字节转换为0到255之间的值
*   [parse\_str](http://php.p2hp.com/manual/zh/function.parse-str.php) - 将字符串解析为变量
*   [print](http://php.p2hp.com/manual/zh/function.print.php) - 输出一个字符串
*   [printf](http://php.p2hp.com/manual/zh/function.printf.php) - 输出格式化的字符串
*   [quoted\_printable\_decode](http://php.p2hp.com/manual/zh/function.quoted-printable-decode.php) - 将带引号的可打印字符串转换为8位字符串
*   [quoted\_printable\_encode](http://php.p2hp.com/manual/zh/function.quoted-printable-encode.php) - 将8位字符串转换为带引号的可打印字符串
*   [quotemeta](http://php.p2hp.com/manual/zh/function.quotemeta.php) - 引用元字符
*   [rtrim](http://php.p2hp.com/manual/zh/function.rtrim.php) - 从字符串末尾删除空格(或其他字符)
*   [setlocale](http://php.p2hp.com/manual/zh/function.setlocale.php) - 设置区域设置信息
*   [sha1\_file](http://php.p2hp.com/manual/zh/function.sha1-file.php) - 计算文件的sha1哈希值
*   [sha1](http://php.p2hp.com/manual/zh/function.sha1.php) - 计算字符串的sha1哈希值
*   [similar\_text](http://php.p2hp.com/manual/zh/function.similar-text.php) - 计算两个字符串之间的相似性
*   [soundex](http://php.p2hp.com/manual/zh/function.soundex.php) - 计算字符串的soundex键
*   [sprintf](http://php.p2hp.com/manual/zh/function.sprintf.php) - 返回格式化的字符串
*   [sscanf](http://php.p2hp.com/manual/zh/function.sscanf.php) - 根据格式从字符串中解析输入
*   [str\_contains](https://php.p2hp.com/manual/zh/function.str-contains.php) - 判断一个字符串包含一个给定的子字符串
*   [str\_ends\_with](https://php.p2hp.com/manual/zh/function.str-ends-with.php) - 检查字符串是否以给定的子字符串结尾
*   [str\_getcsv](http://php.p2hp.com/manual/zh/function.str-getcsv.php) - 将CSV字符串解析为数组
*   [str\_ireplace](http://php.p2hp.com/manual/zh/function.str-ireplace.php) - str\_replace的不区分大小写的版本
*   [str\_pad](http://php.p2hp.com/manual/zh/function.str-pad.php) - 使用另一个字符串将字符串填充到某个长度
*   [str\_repeat](http://php.p2hp.com/manual/zh/function.str-repeat.php) - 重复一个字符串
*   [str\_replace](http://php.p2hp.com/manual/zh/function.str-replace.php) - 用替换字符串替换所有出现的搜索字符串
*   [str\_rot13](http://php.p2hp.com/manual/zh/function.str-rot13.php) - 对字符串执行rot13转换
*   [str\_shuffle](http://php.p2hp.com/manual/zh/function.str-shuffle.php) - 随机调整字符串
*   [str\_split](http://php.p2hp.com/manual/zh/function.str-split.php) - 将字符串转换为数组
*   [str\_starts\_with](https://php.p2hp.com/manual/zh/function.str-starts-with.php) - 检查字符串是否以给定的子字符串开头
*   [str\_word\_count](http://php.p2hp.com/manual/zh/function.str-word-count.php) - 返回有关字符串中使用的单词的信息
*   [strcasecmp](http://php.p2hp.com/manual/zh/function.strcasecmp.php) - 二进制安全不区分大小写的字符串比较
*   [strchr](http://php.p2hp.com/manual/zh/function.strchr.php) - strstr的别名
*   [strcmp](http://php.p2hp.com/manual/zh/function.strcmp.php) - 二进制安全字符串比较
*   [strcoll](http://php.p2hp.com/manual/zh/function.strcoll.php) - 基于区域的字符串比较
*   [strcspn](http://php.p2hp.com/manual/zh/function.strcspn.php) - 查找不匹配掩码的初始段的长度
*   [strip\_tags](http://php.p2hp.com/manual/zh/function.strip-tags.php) - 从字符串中删除 HTML和PHP标记
*   [stripcslashes](http://php.p2hp.com/manual/zh/function.stripcslashes.php) - 使用addcslashes引用的un-quote字符串
*   [stripos](http://php.p2hp.com/manual/zh/function.stripos.php) - 查找字符串中第一次出现不区分大小写的子字符串的位置
*   [stripslashes](http://php.p2hp.com/manual/zh/function.stripslashes.php) - 取消引用带引号的字符串
*   [stristr](http://php.p2hp.com/manual/zh/function.stristr.php) - 不区分大小写的strstr
*   [strlen](http://php.p2hp.com/manual/zh/function.strlen.php) - 获取字符串长度
*   [strnatcasecmp](http://php.p2hp.com/manual/zh/function.strnatcasecmp.php) - 使用“自然顺序”算法进行不区分大小写的字符串比较
*   [strnatcmp](http://php.p2hp.com/manual/zh/function.strnatcmp.php) - 使用“自然顺序”算法进行字符串比较
*   [strncasecmp](http://php.p2hp.com/manual/zh/function.strncasecmp.php) - 前n个字符的二进制安全不区分大小写的字符串比较
*   [strncmp](http://php.p2hp.com/manual/zh/function.strncmp.php) - 前n个字符的二进制安全字符串比较
*   [strpbrk](http://php.p2hp.com/manual/zh/function.strpbrk.php) - 在字符串中搜索任何一组字符
*   [strpos](http://php.p2hp.com/manual/zh/function.strpos.php) - 查找字符串中第一次出现子字符串的位置
*   [strrchr](http://php.p2hp.com/manual/zh/function.strrchr.php) - 查找字符串中最后一个字符
*   [strrev](http://php.p2hp.com/manual/zh/function.strrev.php) - 反转一个字符串
*   [strripos](http://php.p2hp.com/manual/zh/function.strripos.php) - 查找字符串中最后一个不区分大小写的子字符串的位置
*   [strrpos](http://php.p2hp.com/manual/zh/function.strrpos.php) - 查找字符串中最后一次出现的子字符串的位置
*   [strspn](http://php.p2hp.com/manual/zh/function.strspn.php) - 查找字符串的初始段的长度，该字符串完全由给定掩码中包含的字符组成
*   [strstr](http://php.p2hp.com/manual/zh/function.strstr.php) - 查找字符串的第一个匹配项
*   [strtok](http://php.p2hp.com/manual/zh/function.strtok.php) - Tokenize字符串
*   [strtolower](http://php.p2hp.com/manual/zh/function.strtolower.php) - 将字符串设为小写
*   [strtoupper](http://php.p2hp.com/manual/zh/function.strtoupper.php) - 将字符串设为大写
*   [strtr](http://php.p2hp.com/manual/zh/function.strtr.php) - 翻译字符或替换子字符串
*   [substr\_compare](http://php.p2hp.com/manual/zh/function.substr-compare.php) - 从偏移量到最大长度字符的两个字符串的二进制安全比较
*   [substr\_count](http://php.p2hp.com/manual/zh/function.substr-count.php) - 计算子字符串出现次数
*   [substr\_replace](http://php.p2hp.com/manual/zh/function.substr-replace.php) - 替换字符串的一部分内的文本
*   [substr](http://php.p2hp.com/manual/zh/function.substr.php) - 返回字符串的一部分
*   [trim](http://php.p2hp.com/manual/zh/function.trim.php) - 从字符串的开头和结尾去除空格(或其他字符)
*   [ucfirst](http://php.p2hp.com/manual/zh/function.ucfirst.php) - 将字符串的第一个字符设为大写
*   [ucwords](http://php.p2hp.com/manual/zh/function.ucwords.php) - 大写字符串中每个单词的第一个字符
*   [vfprintf](http://php.p2hp.com/manual/zh/function.vfprintf.php) - 将格式化的字符串写入流
*   [vprintf](http://php.p2hp.com/manual/zh/function.vprintf.php) - 输出格式化的字符串
*   [vsprintf](http://php.p2hp.com/manual/zh/function.vsprintf.php) - 返回格式化的字符串
*   [wordwrap](http://php.p2hp.com/manual/zh/function.wordwrap.php) - 将字符串包含给给定数量的字符

  

多字节字符串
------

  

*   [mb\_check\_encoding](http://php.p2hp.com/manual/zh/function.mb-check-encoding.php) - 检查字符串是否对指定的编码有效
*   [mb\_chr](http://php.p2hp.com/manual/zh/function.mb-chr.php) - 获取特定角色
*   [mb\_convert\_case](http://php.p2hp.com/manual/zh/function.mb-convert-case.php) - 对字符串执行大小写折叠
*   [mb\_convert\_encoding](http://php.p2hp.com/manual/zh/function.mb-convert-encoding.php) - 转换字符编码
*   [mb\_convert\_kana](http://php.p2hp.com/manual/zh/function.mb-convert-kana.php) - 将“假名” 换成另一个(“zen-kaku”，“han-kaku”等)
*   [mb\_convert\_variables](http://php.p2hp.com/manual/zh/function.mb-convert-variables.php) - 转换变量中的字符代码
*   [mb\_decode\_mimeheader](http://php.p2hp.com/manual/zh/function.mb-decode-mimeheader.php) - 解码MIME头字段中的字符串
*   [mb\_decode\_numericentity](http://php.p2hp.com/manual/zh/function.mb-decode-numericentity.php) - 解码对字符的HTML数字字符串引用
*   [mb\_detect\_encoding](http://php.p2hp.com/manual/zh/function.mb-detect-encoding.php) - 检测字符编码
*   [mb\_detect\_order](http://php.p2hp.com/manual/zh/function.mb-detect-order.php) - 设置/获取字符编码检测顺序
*   [mb\_encode\_mimeheader](http://php.p2hp.com/manual/zh/function.mb-encode-mimeheader.php) - 为MIME标头编码字符串
*   [mb\_encode\_numericentity](http://php.p2hp.com/manual/zh/function.mb-encode-numericentity.php) - 将字符编码为HTML数字字符串引用
*   [mb\_encoding\_aliases](http://php.p2hp.com/manual/zh/function.mb-encoding-aliases.php) - 获取已知编码类型的别名
*   [mb\_ereg\_match](http://php.p2hp.com/manual/zh/function.mb-ereg-match.php) - 多字节字符串的正则表达式匹配
*   [mb\_ereg\_replace\_callback](http://php.p2hp.com/manual/zh/function.mb-ereg-replace-callback.php) - 执行正则表达式搜索并使用回调替换多字节支持
*   [mb\_ereg\_replace](http://php.p2hp.com/manual/zh/function.mb-ereg-replace.php) - 用多字节支持替换正则表达式
*   [mb\_ereg\_search\_getpos](http://php.p2hp.com/manual/zh/function.mb-ereg-search-getpos.php) - 返回下一个正则表达式匹配的起始点
*   [mb\_ereg\_search\_getregs](http://php.p2hp.com/manual/zh/function.mb-ereg-search-getregs.php) - 从最后一个多字节正则表达式匹配中检索结果
*   [mb\_ereg\_search\_init](http://php.p2hp.com/manual/zh/function.mb-ereg-search-init.php) - 多字节正则表达式匹配的设置字符串和正则表达式
*   [mb\_ereg\_search\_pos](http://php.p2hp.com/manual/zh/function.mb-ereg-search-pos.php) - 返回预定义多字节字符串的多字节正则表达式的匹配部分的位置和长度
*   [mb\_ereg\_search\_regs](http://php.p2hp.com/manual/zh/function.mb-ereg-search-regs.php) - 返回多字节正则表达式的匹配部分
*   [mb\_ereg\_search\_setpos](http://php.p2hp.com/manual/zh/function.mb-ereg-search-setpos.php) - 设置下一个正则表达式匹配的起始点
*   [mb\_ereg\_search](http://php.p2hp.com/manual/zh/function.mb-ereg-search.php) - 用于预定义多字节字符串的多字节正则表达式匹配
*   [mb\_ereg](http://php.p2hp.com/manual/zh/function.mb-ereg.php) - 正则表达式与多字节支持匹配
*   [mb\_eregi\_replace](http://php.p2hp.com/manual/zh/function.mb-eregi-replace.php) - 用多字节支持替换正则表达式忽略大小写
*   [mb\_eregi](http://php.p2hp.com/manual/zh/function.mb-eregi.php) - 正则表达式匹配忽略具有多字节支持的大小写
*   [mb\_get\_info](http://php.p2hp.com/manual/zh/function.mb-get-info.php) - 获取mbstring的内部设置
*   [mb\_http\_input](http://php.p2hp.com/manual/zh/function.mb-http-input.php) - 检测HTTP输入字符编码
*   [mb\_http\_output](http://php.p2hp.com/manual/zh/function.mb-http-output.php) - 设置/获取HTTP输出字符编码
*   [mb\_internal\_encoding](http://php.p2hp.com/manual/zh/function.mb-internal-encoding.php) - 设置/获取内部字符编码
*   [mb\_language](http://php.p2hp.com/manual/zh/function.mb-language.php) - 设置/获取当前语言
*   [mb\_list\_encodings](http://php.p2hp.com/manual/zh/function.mb-list-encodings.php) - 返回所有支持的编码的数组
*   [mb\_ord](http://php.p2hp.com/manual/zh/function.mb-ord.php) - 获取角色的代码点
*   [mb\_output\_handler](http://php.p2hp.com/manual/zh/function.mb-output-handler.php) - 回调函数转换输出缓冲区中的字符编码
*   [mb\_parse\_str](http://php.p2hp.com/manual/zh/function.mb-parse-str.php) - 解析GET/POST/COOKIE数据并设置全局变量
*   [mb\_preferred\_mime\_name](http://php.p2hp.com/manual/zh/function.mb-preferred-mime-name.php) - 获取MIME字符集字符串
*   [mb\_regex\_encoding](http://php.p2hp.com/manual/zh/function.mb-regex-encoding.php) - 为多字节正则表达式设置/获取字符编码
*   [mb\_regex\_set\_options](http://php.p2hp.com/manual/zh/function.mb-regex-set-options.php) - 设置/获取mbregex函数的默认选项
*   [mb\_scrub](http://php.p2hp.com/manual/zh/function.mb-scrub.php) - 说明
*   [mb\_send\_mail](http://php.p2hp.com/manual/zh/function.mb-send-mail.php) - 发送编码邮件
*   [mb\_split](http://php.p2hp.com/manual/zh/function.mb-split.php) - 使用正则表达式拆分多字节字符串
*   [mb\_str\_split](http://php.p2hp.com/manual/zh/function.mb-str-split.php) - 给定一个多字节字符串，返回其字符数组
*   [mb\_strcut](http://php.p2hp.com/manual/zh/function.mb-strcut.php) - 获取字符串的一部分
*   [mb\_strimwidth](http://php.p2hp.com/manual/zh/function.mb-strimwidth.php) - 获取具有指定宽度的截断字符串
*   [mb\_stripos](http://php.p2hp.com/manual/zh/function.mb-stripos.php) - 查找字符串中第一次出现的位置，不区分大小写
*   [mb\_stristr](http://php.p2hp.com/manual/zh/function.mb-stristr.php) - 在另一个字符串中查找第一次出现的字符串，不区分大小写
*   [mb\_strlen](http://php.p2hp.com/manual/zh/function.mb-strlen.php) - 获取字符串长度
*   [mb\_strpos](http://php.p2hp.com/manual/zh/function.mb-strpos.php) - 查找字符串中第一次出现字符串的位置
*   [mb\_strrchr](http://php.p2hp.com/manual/zh/function.mb-strrchr.php) - 查找另一个字符串中字符的最后一次出现
*   [mb\_strrichr](http://php.p2hp.com/manual/zh/function.mb-strrichr.php) - 在另一个字符串中查找字符串中最后一个出现的字符串，不区分大小写
*   [mb\_strripos](http://php.p2hp.com/manual/zh/function.mb-strripos.php) - 查找字符串最后一次出现的位置，不区分大小写
*   [mb\_strrpos](http://php.p2hp.com/manual/zh/function.mb-strrpos.php) - 查找字符串中最后一次出现的字符串的位置
*   [mb\_strstr](http://php.p2hp.com/manual/zh/function.mb-strstr.php) - 查找另一个字符串中的第一个字符串
*   [mb\_strtolower](http://php.p2hp.com/manual/zh/function.mb-strtolower.php) - 将字符串设为小写
*   [mb\_strtoupper](http://php.p2hp.com/manual/zh/function.mb-strtoupper.php) - 将字符串设为大写
*   [mb\_strwidth](http://php.p2hp.com/manual/zh/function.mb-strwidth.php) - 返回字符串的宽度
*   [mb\_substitute\_character](http://php.p2hp.com/manual/zh/function.mb-substitute-character.php) - 设置/获取替换字符
*   [mb\_substr\_count](http://php.p2hp.com/manual/zh/function.mb-substr-count.php) - 计算子字符串出现次数
*   [mb\_substr](http://php.p2hp.com/manual/zh/function.mb-substr.php) - 获取字符串的一部分

  

变量处理
----

  

*   [boolval](http://php.p2hp.com/manual/zh/function.boolval.php) - 获取变量的布尔值
*   [debug\_zval\_dump](http://php.p2hp.com/manual/zh/function.debug-zval-dump.php) - 将内部zend值的字符串表示转储为输出
*   [doubleval](http://php.p2hp.com/manual/zh/function.doubleval.php) - [floatval的](http://php.p2hp.com/manual/zh/function.doubleval.php)别名
*   [empty](http://php.p2hp.com/manual/zh/function.empty.php) - 确定变量是否为空
*   [floatval](http://php.p2hp.com/manual/zh/function.floatval.php) - 获取变量的浮点值
*   [get\_defined\_vars](http://php.p2hp.com/manual/zh/function.get-defined-vars.php) - 返回所有已定义变量的数组
*   [get\_resource\_id](https://php.p2hp.com/manual/zh/function.get-resource-id.php) - 返回一个整数标识符为给定的资源
*   [get\_resource\_type](http://php.p2hp.com/manual/zh/function.get-resource-type.php) - 返回资源类型
*   [get\_debug\_type](#) - 获取变量的类型 -可以为数组，字符串，匿名类和对象返回更有用的输出信息
*   [gettype](http://php.p2hp.com/manual/zh/function.gettype.php) - 获取变量的类型
*   [intval](http://php.p2hp.com/manual/zh/function.intval.php) - 获取变量的整数值
*   [is\_array](http://php.p2hp.com/manual/zh/function.is-array.php) - 查找变量是否为数组
*   [is\_bool](http://php.p2hp.com/manual/zh/function.is-bool.php) - 查找变量是否为布尔值
*   [is\_callable](http://php.p2hp.com/manual/zh/function.is-callable.php) - 验证变量的内容是否可以作为函数调用
*   [is\_countable](http://php.p2hp.com/manual/zh/function.is-countable.php) - 验证变量的内容是否为可数值
*   [is\_double](http://php.p2hp.com/manual/zh/function.is-double.php) - is\_float的别名
*   [is\_float](http://php.p2hp.com/manual/zh/function.is-float.php) - 查找变量的类型是否为float
*   [is\_int](http://php.p2hp.com/manual/zh/function.is-int.php) - 查找变量的类型是否为整数
*   [is\_integer](http://php.p2hp.com/manual/zh/function.is-integer.php) - [is\_int的](http://php.p2hp.com/manual/zh/function.is-integer.php)别名
*   [is\_iterable](http://php.p2hp.com/manual/zh/function.is-iterable.php) - 验证变量的内容是否为可迭代值
*   [is\_long](http://php.p2hp.com/manual/zh/function.is-long.php) - [is\_int的](http://php.p2hp.com/manual/zh/function.is-long.php)别名
*   [is\_null](http://php.p2hp.com/manual/zh/function.is-null.php) - 查找变量是否为NULL
*   [is\_numeric](http://php.p2hp.com/manual/zh/function.is-numeric.php) - 查找变量是数字还是数字字符串
*   [is\_object](http://php.p2hp.com/manual/zh/function.is-object.php) - 查找变量是否为对象
*   [is\_real](http://php.p2hp.com/manual/zh/function.is-real.php) - is\_float的别名
*   [is\_resource](http://php.p2hp.com/manual/zh/function.is-resource.php) - 查找变量是否为资源
*   [is\_scalar](http://php.p2hp.com/manual/zh/function.is-scalar.php) - 查找变量是否为标量
*   [is\_string](http://php.p2hp.com/manual/zh/function.is-string.php) - 查找变量的类型是否为字符串
*   [isset](http://php.p2hp.com/manual/zh/function.isset.php) - 确定变量是否已声明且不同于NULL
*   [print\_r](http://php.p2hp.com/manual/zh/function.print-r.php) - 打印有关变量的可读信息
*   [serialize](http://php.p2hp.com/manual/zh/function.serialize.php) - 生成值的可存储表示
*   [settype](http://php.p2hp.com/manual/zh/function.settype.php) - 设置变量的类型
*   [strval](http://php.p2hp.com/manual/zh/function.strval.php) - 获取变量的字符串值
*   [unserialize](http://php.p2hp.com/manual/zh/function.unserialize.php) - 从存储的表示形式创建PHP值
*   [unset](http://php.p2hp.com/manual/zh/function.unset.php) - 取消设置给定变量
*   [var\_dump](http://php.p2hp.com/manual/zh/function.var-dump.php) - 转储有关变量的信息
*   [var\_export](http://php.p2hp.com/manual/zh/function.var-export.php) - 输出或返回变量的可解析字符串表示形式

  

文件系统
----

  

*   [basename](http://php.p2hp.com/manual/zh/function.basename.php) - 返回路径的尾随名称组件
*   [chgrp](http://php.p2hp.com/manual/zh/function.chgrp.php) - 更改文件组
*   [chmod](http://php.p2hp.com/manual/zh/function.chmod.php) - 更改文件模式
*   [chown](http://php.p2hp.com/manual/zh/function.chown.php) - 更改文件所有者
*   [clearstatcache](http://php.p2hp.com/manual/zh/function.clearstatcache.php) - 清除文件状态缓存
*   [copy](http://php.p2hp.com/manual/zh/function.copy.php) - 复制文件
*   [delete](http://php.p2hp.com/manual/zh/function.delete.php) - 请参阅取消链接或取消设置
*   [dirname](http://php.p2hp.com/manual/zh/function.dirname.php) - 返回父目录的路径
*   [disk\_free\_space](http://php.p2hp.com/manual/zh/function.disk-free-space.php) - 返回文件系统或磁盘分区上的可用空间
*   [disk\_total\_space](http://php.p2hp.com/manual/zh/function.disk-total-space.php) - 返回文件系统或磁盘分区的总大小
*   [diskfreespace](http://php.p2hp.com/manual/zh/function.diskfreespace.php) - [disk\_free\_space的](http://php.p2hp.com/manual/zh/function.diskfreespace.php)别名
*   [fclose](http://php.p2hp.com/manual/zh/function.fclose.php) - 关闭一个打开的文件指针
*   [feof](http://php.p2hp.com/manual/zh/function.feof.php) - 测试文件指针上的文件结尾
*   [fflush](http://php.p2hp.com/manual/zh/function.fflush.php) - 将输出刷新到文件
*   [fgetc](http://php.p2hp.com/manual/zh/function.fgetc.php) - 从文件指针获取字符
*   [fgetcsv](http://php.p2hp.com/manual/zh/function.fgetcsv.php) - 从文件指针获取行并解析CSV字段
*   [fgets](http://php.p2hp.com/manual/zh/function.fgets.php) - 从文件指针获取行
*   [fgetss](http://php.p2hp.com/manual/zh/function.fgetss.php) - 从文件指针获取行并删除HTML标记
*   [file\_exists](http://php.p2hp.com/manual/zh/function.file-exists.php) - 检查文件或目录是否存在
*   [file\_get\_contents](http://php.p2hp.com/manual/zh/function.file-get-contents.php) - 将整个文件读入字符串
*   [file\_put\_contents](http://php.p2hp.com/manual/zh/function.file-put-contents.php) - 将数据写入文件
*   [file](http://php.p2hp.com/manual/zh/function.file.php) - 将整个文件读入数组
*   [fileatime](http://php.p2hp.com/manual/zh/function.fileatime.php) - 获取文件的最后访问时间
*   [filectime](http://php.p2hp.com/manual/zh/function.filectime.php) - 获取文件的inode更改时间
*   [filegroup](http://php.p2hp.com/manual/zh/function.filegroup.php) - 获取文件组
*   [fileinode](http://php.p2hp.com/manual/zh/function.fileinode.php) - 获取文件inode
*   [filemtime](http://php.p2hp.com/manual/zh/function.filemtime.php) - 获取文件修改时间
*   [fileowner](http://php.p2hp.com/manual/zh/function.fileowner.php) - 获取文件所有者
*   [fileperms](http://php.p2hp.com/manual/zh/function.fileperms.php) - 获取文件权限
*   [filesize](http://php.p2hp.com/manual/zh/function.filesize.php) - 获取文件大小
*   [filetype](http://php.p2hp.com/manual/zh/function.filetype.php) - 获取文件类型
*   [flock](http://php.p2hp.com/manual/zh/function.flock.php) - 便携式咨询文件锁定
*   [fnmatch](http://php.p2hp.com/manual/zh/function.fnmatch.php) - 将文件名与模式匹配
*   [fopen](http://php.p2hp.com/manual/zh/function.fopen.php) - 打开文件或URL
*   [fpassthru](http://php.p2hp.com/manual/zh/function.fpassthru.php) - 输出文件指针上的所有剩余数据
*   [fputcsv](http://php.p2hp.com/manual/zh/function.fputcsv.php) - 将行格式化为CSV并写入文件指针
*   [fputs](http://php.p2hp.com/manual/zh/function.fputs.php) - fwrite的别名
*   [fread](http://php.p2hp.com/manual/zh/function.fread.php) - 二进制安全文件读取
*   [fscanf](http://php.p2hp.com/manual/zh/function.fscanf.php) - 根据格式从文件中解析输入
*   [fseek](http://php.p2hp.com/manual/zh/function.fseek.php) - 寻找文件指针
*   [fstat](http://php.p2hp.com/manual/zh/function.fstat.php) - 使用打开的文件指针获取有关文件的信息
*   [ftell](http://php.p2hp.com/manual/zh/function.ftell.php) - 返回文件读/写指针的当前位置
*   [ftruncate](http://php.p2hp.com/manual/zh/function.ftruncate.php) - 将文件截断为给定长度
*   [fwrite](http://php.p2hp.com/manual/zh/function.fwrite.php) - 二进制安全文件写入
*   [glob](http://php.p2hp.com/manual/zh/function.glob.php) - 查找与模式匹配的路径名
*   [is\_dir](http://php.p2hp.com/manual/zh/function.is-dir.php) - 判断文件名是否是目录
*   [is\_executable](http://php.p2hp.com/manual/zh/function.is-executable.php) - 判断文件名是否可执行
*   [is\_file](http://php.p2hp.com/manual/zh/function.is-file.php) - 判断文件名是否是常规文件
*   [is\_link](http://php.p2hp.com/manual/zh/function.is-link.php) - 判断文件名是否为符号链接
*   [is\_readable](http://php.p2hp.com/manual/zh/function.is-readable.php) - 判断文件是否存在且可读
*   [is\_uploaded\_file](http://php.p2hp.com/manual/zh/function.is-uploaded-file.php) - 判断文件是否通过HTTP POST上传
*   [is\_writable](http://php.p2hp.com/manual/zh/function.is-writable.php) - 判断文件名是否可写
*   [is\_writeable](http://php.p2hp.com/manual/zh/function.is-writeable.php) - is\_writable的别名
*   [lchgrp](http://php.p2hp.com/manual/zh/function.lchgrp.php) - 更改符号链接的组所有权
*   [lchown](http://php.p2hp.com/manual/zh/function.lchown.php) - 更改符号链接的用户所有权
*   [link](http://php.p2hp.com/manual/zh/function.link.php) - 创建硬链接
*   [linkinfo](http://php.p2hp.com/manual/zh/function.linkinfo.php) - 获取有关链接的信息
*   [lstat](http://php.p2hp.com/manual/zh/function.lstat.php) - 提供有关文件或符号链接的信息
*   [mkdir](http://php.p2hp.com/manual/zh/function.mkdir.php) - 制作目录
*   [move\_uploaded\_file](http://php.p2hp.com/manual/zh/function.move-uploaded-file.php) - 将上传的文件移动到新位置
*   [parse\_ini\_file](http://php.p2hp.com/manual/zh/function.parse-ini-file.php) - 解析配置文件
*   [parse\_ini\_string](http://php.p2hp.com/manual/zh/function.parse-ini-string.php) - 解析配置字符串
*   [pathinfo](http://php.p2hp.com/manual/zh/function.pathinfo.php) - 返回有关文件路径的信息
*   [pclose](http://php.p2hp.com/manual/zh/function.pclose.php) - 关闭进程文件指针
*   [popen](http://php.p2hp.com/manual/zh/function.popen.php) - 打开进程文件指针
*   [readfile](http://php.p2hp.com/manual/zh/function.readfile.php) - 输出文件
*   [readlink](http://php.p2hp.com/manual/zh/function.readlink.php) - 返回符号链接的目标
*   [realpath\_cache\_get](http://php.p2hp.com/manual/zh/function.realpath-cache-get.php) - 获取realpath缓存条目
*   [realpath\_cache\_size](http://php.p2hp.com/manual/zh/function.realpath-cache-size.php) - 获取实际路径缓存大小
*   [realpath](http://php.p2hp.com/manual/zh/function.realpath.php) - 返回规范化的绝对​​路径名
*   [rename](http://php.p2hp.com/manual/zh/function.rename.php) - 重命名文件或目录
*   [rewind](http://php.p2hp.com/manual/zh/function.rewind.php) - 倒回文件指针的位置
*   [rmdir](http://php.p2hp.com/manual/zh/function.rmdir.php) - 删除目录
*   [set\_file\_buffer](http://php.p2hp.com/manual/zh/function.set-file-buffer.php) - stream\_set\_write\_buffer的别名
*   [stat](http://php.p2hp.com/manual/zh/function.stat.php) - 提供有关文件的信息
*   [symlink](http://php.p2hp.com/manual/zh/function.symlink.php) - 创建符号链接
*   [tempnam](http://php.p2hp.com/manual/zh/function.tempnam.php) - 使用唯一文件名创建文件
*   [tmpfile](http://php.p2hp.com/manual/zh/function.tmpfile.php) - 创建临时文件
*   [touch](http://php.p2hp.com/manual/zh/function.touch.php) - 设置文件的访问和修改时间
*   [umask](http://php.p2hp.com/manual/zh/function.umask.php) - 更改当前的umask
*   [unlink](http://php.p2hp.com/manual/zh/function.unlink.php) - 删除文件

  

目录处理
----


*   [Directory](http://php.p2hp.com/manual/zh/class.directory.php) — Directory 类
    *   [Directory::close](http://php.p2hp.com/manual/zh/directory.close.php) — 释放目录句柄
    *   [Directory::read](http://php.p2hp.com/manual/zh/directory.read.php) — 从目录句柄中读取条目
    *   [Directory::rewind](http://php.p2hp.com/manual/zh/directory.rewind.php) — 倒回目录句柄
*   [目录函数函数](#)
    *   [chdir](http://php.p2hp.com/manual/zh/function.chdir.php) - 更改目录
    *   [chroot](http://php.p2hp.com/manual/zh/function.chroot.php) - 更改根目录
    *   [closedir](http://php.p2hp.com/manual/zh/function.closedir.php) - 关闭目录句柄
    *   [dir](http://php.p2hp.com/manual/zh/function.dir.php) - 返回Directory类的实例
    *   [getcwd](http://php.p2hp.com/manual/zh/function.getcwd.php) - 获取当前工作目录
    *   [opendir](http://php.p2hp.com/manual/zh/function.opendir.php) - 打开目录句柄
    *   [readdir](http://php.p2hp.com/manual/zh/function.readdir.php) - 从目录句柄读取条目
    *   [rewinddir](http://php.p2hp.com/manual/zh/function.rewinddir.php) - 回滚目录句柄
    *   [scandir](http://php.p2hp.com/manual/zh/function.scandir.php) - 列出指定路径中的文件和目录


数学
--

  

*   [abs](http://php.p2hp.com/manual/zh/function.abs.php) - 绝对值
*   [acos](http://php.p2hp.com/manual/zh/function.acos.php) - Arc cosine
*   [acosh](http://php.p2hp.com/manual/zh/function.acosh.php) - 反双曲余弦
*   [asin](http://php.p2hp.com/manual/zh/function.asin.php) - Arc正弦
*   [asinh](http://php.p2hp.com/manual/zh/function.asinh.php) - 反双曲正弦
*   [atan2](http://php.p2hp.com/manual/zh/function.atan2.php) - 两个变量的反正切
*   [atan](http://php.p2hp.com/manual/zh/function.atan.php) - 反正切
*   [atanh](http://php.p2hp.com/manual/zh/function.atanh.php) - 反双曲正切
*   [base\_convert](http://php.p2hp.com/manual/zh/function.base-convert.php) - 在任意碱基之间转换数字
*   [bindec](http://php.p2hp.com/manual/zh/function.bindec.php) - 二进制到十进制
*   [ceil](http://php.p2hp.com/manual/zh/function.ceil.php) - 圆形分数
*   [cos](http://php.p2hp.com/manual/zh/function.cos.php) - 余弦
*   [cosh](http://php.p2hp.com/manual/zh/function.cosh.php) - 双曲余弦
*   [decbin](http://php.p2hp.com/manual/zh/function.decbin.php) - 十进制到二进制
*   [dechex](http://php.p2hp.com/manual/zh/function.dechex.php) - 十进制到十六进制
*   [decoct](http://php.p2hp.com/manual/zh/function.decoct.php) - 十进制到八进制
*   [deg2rad](http://php.p2hp.com/manual/zh/function.deg2rad.php) - 将度数转换为弧度当量
*   [exp](http://php.p2hp.com/manual/zh/function.exp.php) - 计算e的指数
*   [expm1](http://php.p2hp.com/manual/zh/function.expm1.php) - 返回exp(number) - 1，即使number的值接近于零，也以精确的方式计算
*   [floor](http://php.p2hp.com/manual/zh/function.floor.php) - 圆形分数下降
*   [fdiv](http://php.p2hp.com/manual/zh/function.fdiv.php) - 在 IEEE 754 语义下执行浮点除法
*   [fmod](http://php.p2hp.com/manual/zh/function.fmod.php) - 返回参数除法的浮点余数(modulo)
*   [getrandmax](http://php.p2hp.com/manual/zh/function.getrandmax.php) - 显示最大可能的随机值
*   [hexdec](http://php.p2hp.com/manual/zh/function.hexdec.php) - 十六进制到十进制
*   [hypot](http://php.p2hp.com/manual/zh/function.hypot.php) - 计算直角三角形的斜边长度
*   [intdiv](http://php.p2hp.com/manual/zh/function.intdiv.php) - 整数分部
*   [is\_finite](http://php.p2hp.com/manual/zh/function.is-finite.php) - 查找值是否为合法有限数
*   [is\_infinite](http://php.p2hp.com/manual/zh/function.is-infinite.php) - 查找值是否为无限
*   [is\_nan](http://php.p2hp.com/manual/zh/function.is-nan.php) - 查找值是否不是数字
*   [lcg\_value](http://php.p2hp.com/manual/zh/function.lcg-value.php) - 组合线性同余生成器
*   [log10](http://php.p2hp.com/manual/zh/function.log10.php) - Base-10对数
*   [log1p](http://php.p2hp.com/manual/zh/function.log1p.php) - 返回log(1 + number)，即使number的值接近于零，也以精确的方式计算
*   [log](http://php.p2hp.com/manual/zh/function.log.php) - 自然对数
*   [max](http://php.p2hp.com/manual/zh/function.max.php) - 找到最高价值
*   [min](http://php.p2hp.com/manual/zh/function.min.php) - 找到最低价值
*   [mt\_getrandmax](http://php.p2hp.com/manual/zh/function.mt-getrandmax.php) - 显示最大可能的随机值
*   [mt\_rand](http://php.p2hp.com/manual/zh/function.mt-rand.php) - 通过Mersenne Twister随机数生成器生成随机值
*   [mt\_srand](http://php.p2hp.com/manual/zh/function.mt-srand.php) - 播种Mersenne Twister随机数发生器
*   [octdec](http://php.p2hp.com/manual/zh/function.octdec.php) - 八进制到十进制
*   [pi](http://php.p2hp.com/manual/zh/function.pi.php) - 获得pi的价值
*   [pow](http://php.p2hp.com/manual/zh/function.pow.php) - 指数表达式
*   [rad2deg](http://php.p2hp.com/manual/zh/function.rad2deg.php) - 将弧度数转换为以度为单位的等效数
*   [rand](http://php.p2hp.com/manual/zh/function.rand.php) - 生成随机整数
*   [round](http://php.p2hp.com/manual/zh/function.round.php) - 对浮点数进行四舍五入
*   [sin](http://php.p2hp.com/manual/zh/function.sin.php) - 正弦
*   [sinh](http://php.p2hp.com/manual/zh/function.sinh.php) - 双曲正弦
*   [sqrt](http://php.p2hp.com/manual/zh/function.sqrt.php) - 平方根
*   [srand](http://php.p2hp.com/manual/zh/function.srand.php) - 播种随机数生成器
*   [tan](http://php.p2hp.com/manual/zh/function.tan.php) - Tangent
*   [tanh](http://php.p2hp.com/manual/zh/function.tanh.php) - 双曲正切

  

类和对象
----

  

*   [\_\_autoload](http://php.p2hp.com/manual/zh/function.autoload.php) - 尝试加载未定义的类
*   [class\_alias](http://php.p2hp.com/manual/zh/function.class-alias.php) - 为类创建别名
*   [class\_exists](http://php.p2hp.com/manual/zh/function.class-exists.php) - 检查是否已定义类
*   [get\_called\_class](http://php.p2hp.com/manual/zh/function.get-called-class.php) - “Late Static Binding”类名
*   [get\_class\_methods](http://php.p2hp.com/manual/zh/function.get-class-methods.php) - 获取类方法的名称
*   [get\_class\_vars](http://php.p2hp.com/manual/zh/function.get-class-vars.php) - 获取类的默认属性
*   [get\_class](http://php.p2hp.com/manual/zh/function.get-class.php) - 返回对象类的名称
*   [get\_declared\_classes](http://php.p2hp.com/manual/zh/function.get-declared-classes.php) - 返回具有已定义类名称的数组
*   [get\_declared\_interfaces](http://php.p2hp.com/manual/zh/function.get-declared-interfaces.php) - 返回所有声明的接口的数组
*   [get\_declared\_traits](http://php.p2hp.com/manual/zh/function.get-declared-traits.php) - 返回所有声明的特征的数组
*   [get\_mangled\_object\_vars](#) - 它返回的结果与 (array) $object 相同， 但忽略重载数组强制转换（如 ArrayObject 使用）。 输出也类似于 get\_object\_vars（），但它也显示受保护的和私有字段
*   [get\_object\_vars](http://php.p2hp.com/manual/zh/function.get-object-vars.php) - 获取给定对象的属性
*   [get\_parent\_class](http://php.p2hp.com/manual/zh/function.get-parent-class.php) - 检索对象或类的父类名
*   [interface\_exists](http://php.p2hp.com/manual/zh/function.interface-exists.php) - 检查接口是否已定义
*   [is\_a](http://php.p2hp.com/manual/zh/function.is-a.php) - 检查对象是否属于此类，或者将此类作为其父类之一
*   [is\_subclass\_of](http://php.p2hp.com/manual/zh/function.is-subclass-of.php) - 检查对象是否将此类作为其父类之一或实现它
*   [method\_exists](http://php.p2hp.com/manual/zh/function.method-exists.php) - 检查类方法是否存在
*   [property\_exists](http://php.p2hp.com/manual/zh/function.property-exists.php) - 检查对象或类是否具有属性
*   [trait\_exists](http://php.p2hp.com/manual/zh/function.trait-exists.php) - 检查特征是否存在

  

字符类型检测Ctype
-----------

  

*   [ctype\_alnum](http://php.p2hp.com/manual/zh/function.ctype-alnum.php) - 检查字母数字字符
*   [ctype\_alpha](http://php.p2hp.com/manual/zh/function.ctype-alpha.php) - 检查字母字符
*   [ctype\_cntrl](http://php.p2hp.com/manual/zh/function.ctype-cntrl.php) - 检查控制字符
*   [ctype\_digit](http://php.p2hp.com/manual/zh/function.ctype-digit.php) - 检查数字字符
*   [ctype\_graph](http://php.p2hp.com/manual/zh/function.ctype-graph.php) - 检查除空格外的任何可打印字符
*   [ctype\_lower](http://php.p2hp.com/manual/zh/function.ctype-lower.php) - 检查小写字符
*   [ctype\_print](http://php.p2hp.com/manual/zh/function.ctype-print.php) - 检查可打印字符
*   [ctype\_punct](http://php.p2hp.com/manual/zh/function.ctype-punct.php) - 检查任何非空白字符或字母数字字符的可打印字符
*   [ctype\_space](http://php.p2hp.com/manual/zh/function.ctype-space.php) - 检查空格字符
*   [ctype\_upper](http://php.p2hp.com/manual/zh/function.ctype-upper.php) - 检查大写字符
*   [ctype\_xdigit](http://php.p2hp.com/manual/zh/function.ctype-xdigit.php) - 检查表示十六进制数字的字符

  

日期和时间[(more)](http://php.p2hp.com/manual/zh/book.datetime.php)
--------------------------------------------------------------

  

*   [checkdate](http://php.p2hp.com/manual/zh/function.checkdate.php) - 验证公历日期
*   [date\_add](http://php.p2hp.com/manual/zh/function.date-add.php) - DateTime::add的别名
*   [date\_create\_from\_format](http://php.p2hp.com/manual/zh/function.date-create-from-format.php) - DateTime::createFromFormat的别名
*   [date\_create\_immutable\_from\_format](http://php.p2hp.com/manual/zh/function.date-create-immutable-from-format.php) - DateTimeImmutable::createFromFormat的别名
*   [date\_create\_immutable](http://php.p2hp.com/manual/zh/function.date-create-immutable.php) - DateTimeImmutable::\_\_construct的别名
*   [date\_create](http://php.p2hp.com/manual/zh/function.date-create.php) - DateTime::\_\_construct的别名
*   [date\_date\_set](http://php.p2hp.com/manual/zh/function.date-date-set.php) - DateTime::setDate的别名
*   [date\_default\_timezone\_get](http://php.p2hp.com/manual/zh/function.date-default-timezone-get.php) - 获取脚本中所有日期/时间函数使用的默认时区
*   [date\_default\_timezone\_set](http://php.p2hp.com/manual/zh/function.date-default-timezone-set.php) - 设置脚本中所有日期/时间函数使用的默认时区
*   [date\_diff](http://php.p2hp.com/manual/zh/function.date-diff.php) - DateTime::diff的别名
*   [date\_format](http://php.p2hp.com/manual/zh/function.date-format.php) - DateTime::format的别名
*   [date\_get\_last\_errors](http://php.p2hp.com/manual/zh/function.date-get-last-errors.php) - DateTime::getLastErrors的别名
*   [date\_interval\_create\_from\_date\_string](http://php.p2hp.com/manual/zh/function.date-interval-create-from-date-string.php) - DateInterval::createFromDateString的别名
*   [date\_interval\_format](http://php.p2hp.com/manual/zh/function.date-interval-format.php) - DateInterval::format的别名
*   [date\_isodate\_set](http://php.p2hp.com/manual/zh/function.date-isodate-set.php) - DateTime::setISODate的别名
*   [date\_modify](http://php.p2hp.com/manual/zh/function.date-modify.php) - DateTime::modify的别名
*   [date\_offset\_get](http://php.p2hp.com/manual/zh/function.date-offset-get.php) - DateTime::getOffset的别名
*   [date\_parse\_from\_format](http://php.p2hp.com/manual/zh/function.date-parse-from-format.php) - 获取有关根据指定格式格式化的给定日期的信息
*   [date\_parse](http://php.p2hp.com/manual/zh/function.date-parse.php) - 返回关联数组，其中包含有关给定日期的详细信息
*   [date\_sub](http://php.p2hp.com/manual/zh/function.date-sub.php) - DateTime::sub的别名
*   [date\_sun\_info](http://php.p2hp.com/manual/zh/function.date-sun-info.php) - 返回一个数组，其中包含有关日落/日出和黄昏开始/结束的信息
*   [date\_sunrise](http://php.p2hp.com/manual/zh/function.date-sunrise.php) - 返回给定日期和位置的日出时间
*   [date\_sunset](http://php.p2hp.com/manual/zh/function.date-sunset.php) - 返回给定日期和位置的日落时间
*   [date\_time\_set](http://php.p2hp.com/manual/zh/function.date-time-set.php) - DateTime::setTime的别名
*   [date\_timestamp\_get](http://php.p2hp.com/manual/zh/function.date-timestamp-get.php) - DateTime::getTimestamp的别名
*   [date\_timestamp\_set](http://php.p2hp.com/manual/zh/function.date-timestamp-set.php) - DateTime::setTimestamp的别名
*   [date\_timezone\_get](http://php.p2hp.com/manual/zh/function.date-timezone-get.php) - DateTime::getTimezone的别名
*   [date\_timezone\_set](http://php.p2hp.com/manual/zh/function.date-timezone-set.php) - DateTime::setTimezone的别名
*   [date](http://php.p2hp.com/manual/zh/function.date.php) - 格式化本地时间/日期
*   [getdate](http://php.p2hp.com/manual/zh/function.getdate.php) - 获取日期/时间信息
*   [gettimeofday](http://php.p2hp.com/manual/zh/function.gettimeofday.php) - 获取当前时间
*   [gmdate](http://php.p2hp.com/manual/zh/function.gmdate.php) - 格式化GMT/UTC日期/时间
*   [gmmktime](http://php.p2hp.com/manual/zh/function.gmmktime.php) - 获取GMT日期的Unix时间戳
*   [gmstrftime](http://php.p2hp.com/manual/zh/function.gmstrftime.php) - 根据区域设置格式化GMT/UTC时间/日期
*   [idate](http://php.p2hp.com/manual/zh/function.idate.php) - 将本地时间/日期格式化为整数
*   [localtime](http://php.p2hp.com/manual/zh/function.localtime.php) - 获取当地时间
*   [microtime](http://php.p2hp.com/manual/zh/function.microtime.php) - 返回当前的Unix时间戳，以微秒为单位
*   [mktime](http://php.p2hp.com/manual/zh/function.mktime.php) - 获取日期的Unix时间戳
*   [strftime](http://php.p2hp.com/manual/zh/function.strftime.php) - 根据区域设置格式化本地时间/日期
*   [strptime](http://php.p2hp.com/manual/zh/function.strptime.php) - 解析strftime生成的时间/日期
*   [strtotime](http://php.p2hp.com/manual/zh/function.strtotime.php) - 将任何英文文本日期时间描述解析为Unix时间戳
*   [time](http://php.p2hp.com/manual/zh/function.time.php) - 返回当前的Unix时间戳
*   [timezone\_abbreviations\_list](http://php.p2hp.com/manual/zh/function.timezone-abbreviations-list.php) - DateTimeZone::listAbbreviations的别名
*   [timezone\_identifiers\_list](http://php.p2hp.com/manual/zh/function.timezone-identifiers-list.php) - DateTimeZone::listIdentifiers的别名
*   [timezone\_location\_get](http://php.p2hp.com/manual/zh/function.timezone-location-get.php) - DateTimeZone::getLocation的别名
*   [timezone\_name\_from\_abbr](http://php.p2hp.com/manual/zh/function.timezone-name-from-abbr.php) - 从缩写返回时区名称
*   [timezone\_name\_get](http://php.p2hp.com/manual/zh/function.timezone-name-get.php) - DateTimeZone::getName的别名
*   [timezone\_offset\_get](http://php.p2hp.com/manual/zh/function.timezone-offset-get.php) - DateTimeZone::getOffset的别名
*   [timezone\_open](http://php.p2hp.com/manual/zh/function.timezone-open.php) - DateTimeZone::\_\_construct的别名
*   [timezone\_transitions\_get](http://php.p2hp.com/manual/zh/function.timezone-transitions-get.php) - DateTimeZone::getTransitions的别名
*   [timezone\_version\_get](http://php.p2hp.com/manual/zh/function.timezone-version-get.php) - 获取timezonedb的版本

  

CURL
----

  

*   [curl\_close](http://php.p2hp.com/manual/zh/function.curl-close.php) - 关闭cURL会话
*   [curl\_copy\_handle](http://php.p2hp.com/manual/zh/function.curl-copy-handle.php) - 复制cURL句柄及其所有首选项
*   [curl\_errno](http://php.p2hp.com/manual/zh/function.curl-errno.php) - 返回最后一个错误号
*   [curl\_error](http://php.p2hp.com/manual/zh/function.curl-error.php) - 返回包含当前会话的最后一个错误的字符串
*   [curl\_escape](http://php.p2hp.com/manual/zh/function.curl-escape.php) - URL对给定字符串进行编码
*   [curl\_exec](http://php.p2hp.com/manual/zh/function.curl-exec.php) - 执行cURL会话
*   [curl\_file\_create](http://php.p2hp.com/manual/zh/function.curl-file-create.php) - 创建CURLFile对象
*   [curl\_getinfo](http://php.p2hp.com/manual/zh/function.curl-getinfo.php) - 获取有关特定转移的信息
*   [curl\_init](http://php.p2hp.com/manual/zh/function.curl-init.php) - 初始化cURL会话
*   [curl\_multi\_add\_handle](http://php.p2hp.com/manual/zh/function.curl-multi-add-handle.php) - 将正常的cURL句柄添加到cURL多句柄
*   [curl\_multi\_close](http://php.p2hp.com/manual/zh/function.curl-multi-close.php) - 关闭一组cURL句柄
*   [curl\_multi\_errno](http://php.p2hp.com/manual/zh/function.curl-multi-errno.php) - 返回最后一个多卷曲错误号
*   [curl\_multi\_exec](http://php.p2hp.com/manual/zh/function.curl-multi-exec.php) - 运行当前cURL句柄的子连接
*   [curl\_multi\_getcontent](http://php.p2hp.com/manual/zh/function.curl-multi-getcontent.php) - 如果设置了CURLOPT\_RETURNTRANSFER，则返回cURL句柄的内容
*   [curl\_multi\_info\_read](http://php.p2hp.com/manual/zh/function.curl-multi-info-read.php) - 获取有关当前传输的信息
*   [curl\_multi\_init](http://php.p2hp.com/manual/zh/function.curl-multi-init.php) - 返回一个新的cURL多句柄
*   [curl\_multi\_remove\_handle](http://php.p2hp.com/manual/zh/function.curl-multi-remove-handle.php) - 从一组cURL句柄中删除多个句柄
*   [curl\_multi\_select](http://php.p2hp.com/manual/zh/function.curl-multi-select.php) - 等待任何curl\_multi连接上的活动
*   [curl\_multi\_setopt](http://php.p2hp.com/manual/zh/function.curl-multi-setopt.php) - 为cURL多句柄设置一个选项
*   [curl\_multi\_strerror](http://php.p2hp.com/manual/zh/function.curl-multi-strerror.php) - 返回描述错误代码的字符串
*   [curl\_pause](http://php.p2hp.com/manual/zh/function.curl-pause.php) - 暂停和取消暂停连接
*   [curl\_reset](http://php.p2hp.com/manual/zh/function.curl-reset.php) - 重置libcurl会话句柄的所有选项
*   [curl\_setopt\_array](http://php.p2hp.com/manual/zh/function.curl-setopt-array.php) - 为cURL传输设置多个选项
*   [curl\_setopt](http://php.p2hp.com/manual/zh/function.curl-setopt.php) - 设置cURL传输的选项
*   [curl\_share\_close](http://php.p2hp.com/manual/zh/function.curl-share-close.php) - 关闭cURL共享句柄
*   [curl\_share\_errno](http://php.p2hp.com/manual/zh/function.curl-share-errno.php) - 返回最后一个共享卷曲错误号
*   [curl\_share\_init](http://php.p2hp.com/manual/zh/function.curl-share-init.php) - 初始化cURL共享句柄
*   [curl\_share\_setopt](http://php.p2hp.com/manual/zh/function.curl-share-setopt.php) - 为cURL共享句柄设置一个选项
*   [curl\_share\_strerror](http://php.p2hp.com/manual/zh/function.curl-share-strerror.php) - 返回描述给定错误代码的字符串
*   [curl\_strerror](http://php.p2hp.com/manual/zh/function.curl-strerror.php) - 返回描述给定错误代码的字符串
*   [curl\_unescape](http://php.p2hp.com/manual/zh/function.curl-unescape.php) - 解码给定的URL编码字符串
*   [curl\_version](http://php.p2hp.com/manual/zh/function.curl-version.php) - 获取cURL版本信息

*   [CURLFile](http://php.p2hp.com/manual/zh/class.curlfile.php) — CURLFile 类
    *   [CURLFile::\_\_construct](http://php.p2hp.com/manual/zh/curlfile.construct.php) — 创建 CURLFile 对象
    *   [CURLFile::getFilename](http://php.p2hp.com/manual/zh/curlfile.getfilename.php) — 获取被上传文件的 文件名
    *   [CURLFile::getMimeType](http://php.p2hp.com/manual/zh/curlfile.getmimetype.php) — 获取被上传文件的 MIME 类型
    *   [CURLFile::getPostFilename](http://php.p2hp.com/manual/zh/curlfile.getpostfilename.php) — 获取 POST 请求时使用的 文件名
    *   [CURLFile::setMimeType](http://php.p2hp.com/manual/zh/curlfile.setmimetype.php) — 设置被上传文件的 MIME 类型
    *   [CURLFile::setPostFilename](http://php.p2hp.com/manual/zh/curlfile.setpostfilename.php) — 设置 POST 请求时使用的文件名


过滤器Filter
---------

  

*   [filter\_has\_var](http://php.p2hp.com/manual/zh/function.filter-has-var.php) - 检查指定类型的变量是否存在
*   [filter\_id](http://php.p2hp.com/manual/zh/function.filter-id.php) - 返回属于命名过滤器的过滤器ID
*   [filter\_input\_array](http://php.p2hp.com/manual/zh/function.filter-input-array.php) - 获取外部变量并可选择过滤它们
*   [filter\_input](http://php.p2hp.com/manual/zh/function.filter-input.php) - 按名称获取特定的外部变量，并可选择对其进行过滤
*   [filter\_list](http://php.p2hp.com/manual/zh/function.filter-list.php) - 返回所有支持的过滤器的列表
*   [filter\_var\_array](http://php.p2hp.com/manual/zh/function.filter-var-array.php) - 获取多个变量并可选择过滤它们
*   [filter\_var](http://php.p2hp.com/manual/zh/function.filter-var.php) - 使用指定的过滤器过滤变量

  

函数处理
----

  

*   [call\_user\_func\_array](http://php.p2hp.com/manual/zh/function.call-user-func-array.php) - 使用参数数组调用回调
*   [call\_user\_func](http://php.p2hp.com/manual/zh/function.call-user-func.php) - 调用第一个参数给出的回调
*   [create\_function](http://php.p2hp.com/manual/zh/function.create-function.php) - 创建一个匿名(lambda样式)函数
*   [forward\_static\_call\_array](http://php.p2hp.com/manual/zh/function.forward-static-call-array.php) - 调用静态方法并将参数作为数组传递
*   [forward\_static\_call](http://php.p2hp.com/manual/zh/function.forward-static-call.php) - 调用静态方法
*   [func\_get\_arg](http://php.p2hp.com/manual/zh/function.func-get-arg.php) - 从参数列表中返回一个项目
*   [func\_get\_args](http://php.p2hp.com/manual/zh/function.func-get-args.php) - 返回包含函数参数列表的数组
*   [func\_num\_args](http://php.p2hp.com/manual/zh/function.func-num-args.php) - 返回传递给函数的参数个数
*   [function\_exists](http://php.p2hp.com/manual/zh/function.function-exists.php) - 如果已定义给定函数，则返回TRUE
*   [get\_defined\_functions](http://php.p2hp.com/manual/zh/function.get-defined-functions.php) - 返回所有已定义函数的数组
*   [register\_shutdown\_function](http://php.p2hp.com/manual/zh/function.register-shutdown-function.php) - 注册一个在关机时执行的函数
*   [register\_tick\_function](http://php.p2hp.com/manual/zh/function.register-tick-function.php) - 在每个tick上注册一个执行函数
*   [unregister\_tick\_function](http://php.p2hp.com/manual/zh/function.unregister-tick-function.php) - 取消注册每个tick上执行的函数

  

正则处理PCRE
--------

  

*   [preg\_filter](http://php.p2hp.com/manual/zh/function.preg-filter.php) - 执行正则表达式搜索和替换
*   [preg\_grep](http://php.p2hp.com/manual/zh/function.preg-grep.php) - 返回与模式匹配的数组条目
*   [preg\_last\_error](http://php.p2hp.com/manual/zh/function.preg-last-error.php) - 返回上一次PCRE正则表达式执行的错误代码
*   [preg\_last\_error\_msg](https://php.p2hp.com/manual/zh/function.preg-last-error-msg.php) - 返回上一次PCRE正则表达式执行的错误消息
*   [preg\_match\_all](http://php.p2hp.com/manual/zh/function.preg-match-all.php) - 执行全局正则表达式匹配
*   [preg\_match](http://php.p2hp.com/manual/zh/function.preg-match.php) - 执行正则表达式匹配
*   [preg\_quote](http://php.p2hp.com/manual/zh/function.preg-quote.php) - 引用正则表达式字符
*   [preg\_replace\_callback\_array](http://php.p2hp.com/manual/zh/function.preg-replace-callback-array.php) - 执行正则表达式搜索并使用回调替换
*   [preg\_replace\_callback](http://php.p2hp.com/manual/zh/function.preg-replace-callback.php) - 执行正则表达式搜索并使用回调替换
*   [preg\_replace](http://php.p2hp.com/manual/zh/function.preg-replace.php) - 执行正则表达式搜索和替换
*   [preg\_split](http://php.p2hp.com/manual/zh/function.preg-split.php) - 按正则表达式拆分字符串

  

网络Network
---------

  

*   [checkdnsrr](http://php.p2hp.com/manual/zh/function.checkdnsrr.php) - 检查与给定Internet主机名或IP地址对应的DNS记录
*   [closelog](http://php.p2hp.com/manual/zh/function.closelog.php) - 关闭与系统记录器的连接
*   [define\_syslog\_variables](http://php.p2hp.com/manual/zh/function.define-syslog-variables.php) - 初始化所有与syslog相关的变量
*   [dns\_check\_record](http://php.p2hp.com/manual/zh/function.dns-check-record.php) - checkdnsrr的别名
*   [dns\_get\_mx](http://php.p2hp.com/manual/zh/function.dns-get-mx.php) - [getmxrr的](http://php.p2hp.com/manual/zh/function.dns-get-mx.php)别名
*   [dns\_get\_record](http://php.p2hp.com/manual/zh/function.dns-get-record.php) - 获取与主机名关联的DNS资源记录
*   [fsockopen](http://php.p2hp.com/manual/zh/function.fsockopen.php) - 打开Internet或Unix域套接字连接
*   [gethostbyaddr](http://php.p2hp.com/manual/zh/function.gethostbyaddr.php) - 获取与给定IP地址对应的Internet主机名
*   [gethostbyname](http://php.p2hp.com/manual/zh/function.gethostbyname.php) - 获取与给定Internet主机名对应的IPv4地址
*   [gethostbynamel](http://php.p2hp.com/manual/zh/function.gethostbynamel.php) - 获取与给定Internet主机名对应的IPv4地址列表
*   [gethostname](http://php.p2hp.com/manual/zh/function.gethostname.php) - 获取主机名
*   [getmxrr](http://php.p2hp.com/manual/zh/function.getmxrr.php) - 获取与给定Internet主机名对应的MX记录
*   [getprotobyname](http://php.p2hp.com/manual/zh/function.getprotobyname.php) - 获取与协议名称关联的协议号
*   [getprotobynumber](http://php.p2hp.com/manual/zh/function.getprotobynumber.php) - 获取与协议号关联的协议名称
*   [getservbyname](http://php.p2hp.com/manual/zh/function.getservbyname.php) - 获取与Internet服务和协议关联的端口号
*   [getservbyport](http://php.p2hp.com/manual/zh/function.getservbyport.php) - 获取与端口和协议对应的Internet服务
*   [header\_register\_callback](http://php.p2hp.com/manual/zh/function.header-register-callback.php) - 调用头函数
*   [header\_remove](http://php.p2hp.com/manual/zh/function.header-remove.php) - 删除以前设置的标头
*   [header](http://php.p2hp.com/manual/zh/function.header.php) - 发送原始HTTP标头
*   [headers\_list](http://php.p2hp.com/manual/zh/function.headers-list.php) - 返回已发送(或准备发送)的响应头列表
*   [headers\_sent](http://php.p2hp.com/manual/zh/function.headers-sent.php) - 检查标头是否或已经发送到何处
*   [http\_response\_code](http://php.p2hp.com/manual/zh/function.http-response-code.php) - 获取或设置HTTP响应代码
*   [inet\_ntop](http://php.p2hp.com/manual/zh/function.inet-ntop.php) - 将打包的Internet地址转换为人类可读的表示形式
*   [inet\_pton](http://php.p2hp.com/manual/zh/function.inet-pton.php) - 将人类可读的IP地址转换为其压缩的in\_addr表示形式
*   [ip2long](http://php.p2hp.com/manual/zh/function.ip2long.php) - 将包含(IPv4)Internet协议虚线地址的字符串转换为长整数
*   [long2ip](http://php.p2hp.com/manual/zh/function.long2ip.php) - 将长整数地址转换为(IPv4)Internet标准点分格式的字符串
*   [openlog](http://php.p2hp.com/manual/zh/function.openlog.php) - 打开与系统记录器的连接
*   [pfsockopen](http://php.p2hp.com/manual/zh/function.pfsockopen.php) - 打开持久Internet或Unix域套接字连接
*   [setcookie](http://php.p2hp.com/manual/zh/function.setcookie.php) - 发送cookie
*   [setrawcookie](http://php.p2hp.com/manual/zh/function.setrawcookie.php) - 发送cookie而不用urlencoding cookie值
*   [socket\_get\_status](http://php.p2hp.com/manual/zh/function.socket-get-status.php) - stream\_get\_meta\_data的别名
*   [socket\_set\_blocking](http://php.p2hp.com/manual/zh/function.socket-set-blocking.php) - stream\_set\_blocking的别名
*   [socket\_set\_timeout](http://php.p2hp.com/manual/zh/function.socket-set-timeout.php) - stream\_set\_timeout的别名
*   [syslog](http://php.p2hp.com/manual/zh/function.syslog.php) - 生成系统日志消息

  

程序执行
----

以加锁方式打开的文件(特别是在打开会话时)， 必须在执行后台程序之前关闭。  

*   [escapeshellarg](http://php.p2hp.com/manual/zh/function.escapeshellarg.php) - 转义一个字符串以用作shell参数
*   [escapeshellcmd](http://php.p2hp.com/manual/zh/function.escapeshellcmd.php) - 转义shell元字符
*   [exec](http://php.p2hp.com/manual/zh/function.exec.php) - 执行外部程序
*   [passthru](http://php.p2hp.com/manual/zh/function.passthru.php) - 执行外部程序并显示原始输出
*   [proc\_close](http://php.p2hp.com/manual/zh/function.proc-close.php) - 关闭proc\_open打开的进程并返回该进程的退出代码
*   [proc\_get\_status](http://php.p2hp.com/manual/zh/function.proc-get-status.php) - 获取有关proc\_open打开的进程的信息
*   [proc\_nice](http://php.p2hp.com/manual/zh/function.proc-nice.php) - 更改当前进程的优先级
*   [proc\_open](http://php.p2hp.com/manual/zh/function.proc-open.php) - 执行命令并打开输入/输出的文件指针
*   [proc\_terminate](http://php.p2hp.com/manual/zh/function.proc-terminate.php) - 终止proc\_open打开的进程
*   [shell\_exec](http://php.p2hp.com/manual/zh/function.shell-exec.php) - 通过shell执行命令并将完整输出作为字符串返回
*   [system](http://php.p2hp.com/manual/zh/function.system.php) - 执行外部程序并显示输出

  

PHP选项和信息
--------

  

*   [assert\_options](http://php.p2hp.com/manual/zh/function.assert-options.php) - 设置/获取各种断言标志
*   [assert](http://php.p2hp.com/manual/zh/function.assert.php) - 检查断言是否为FALSE
*   [cli\_get\_process\_title](http://php.p2hp.com/manual/zh/function.cli-get-process-title.php) - 返回当前进程标题
*   [cli\_set\_process\_title](http://php.p2hp.com/manual/zh/function.cli-set-process-title.php) - 设置进程标题
*   [dl](http://php.p2hp.com/manual/zh/function.dl.php) - 在运行时加载PHP扩展
*   [extension\_loaded](http://php.p2hp.com/manual/zh/function.extension-loaded.php) - 找出是否加载了扩展名
*   [gc\_collect\_cycles](http://php.p2hp.com/manual/zh/function.gc-collect-cycles.php) - 强制收集任何现有的垃圾循环
*   [gc\_disable](http://php.p2hp.com/manual/zh/function.gc-disable.php) - 取消激活循环引用收集器
*   [gc\_enable](http://php.p2hp.com/manual/zh/function.gc-enable.php) - 激活循环引用收集器
*   [gc\_enabled](http://php.p2hp.com/manual/zh/function.gc-enabled.php) - 返回循环引用收集器的状态
*   [gc\_mem\_caches](http://php.p2hp.com/manual/zh/function.gc-mem-caches.php) - 回收Zend Engine内存管理器使用的内存
*   [gc\_status](http://php.p2hp.com/manual/zh/function.gc-status.php) - 获取有关垃圾收集器的信息
*   [get\_cfg\_var](http://php.p2hp.com/manual/zh/function.get-cfg-var.php) - 获取PHP配置选项的值
*   [get\_current\_user](http://php.p2hp.com/manual/zh/function.get-current-user.php) - 获取当前PHP脚本的所有者的名称
*   [get\_defined\_constants](http://php.p2hp.com/manual/zh/function.get-defined-constants.php) - 返回一个关联数组，其中包含所有常量及其值的名称
*   [get\_extension\_funcs](http://php.p2hp.com/manual/zh/function.get-extension-funcs.php) - 返回一个包含模块函数名称的数组
*   [get\_include\_path](http://php.p2hp.com/manual/zh/function.get-include-path.php) - 获取当前的include\_path配置选项
*   [get\_included\_files](http://php.p2hp.com/manual/zh/function.get-included-files.php) - 返回包含所包含或必需文件名称的数组
*   [get\_loaded\_extensions](http://php.p2hp.com/manual/zh/function.get-loaded-extensions.php) - 返回一个数组，其中包含已编译和加载的所有模块的名称
*   [get\_magic\_quotes\_gpc](http://php.p2hp.com/manual/zh/function.get-magic-quotes-gpc.php) - 获取magic\_quotes\_gpc的当前配置设置
*   [get\_required\_files](http://php.p2hp.com/manual/zh/function.get-required-files.php) - get\_included\_files的别名
*   [get\_resources](http://php.p2hp.com/manual/zh/function.get-resources.php) - 返回活动资源
*   [getenv](http://php.p2hp.com/manual/zh/function.getenv.php) - 获取环境变量的值
*   [getlastmod](http://php.p2hp.com/manual/zh/function.getlastmod.php) - 获取最后一页修改的时间
*   [getmygid](http://php.p2hp.com/manual/zh/function.getmygid.php) - 获取PHP脚本所有者的GID
*   [getmyinode](http://php.p2hp.com/manual/zh/function.getmyinode.php) - 获取当前脚本的inode
*   [getmypid](http://php.p2hp.com/manual/zh/function.getmypid.php) - 获取PHP的进程ID
*   [getmyuid](http://php.p2hp.com/manual/zh/function.getmyuid.php) - 获取PHP脚本所有者的UID
*   [getopt](http://php.p2hp.com/manual/zh/function.getopt.php) - 从命令行参数列表中获取选项
*   [getrusage](http://php.p2hp.com/manual/zh/function.getrusage.php) - 获取当前资源使用情况
*   [ini\_alter](http://php.p2hp.com/manual/zh/function.ini-alter.php) - ini\_set的别名
*   [ini\_get\_all](http://php.p2hp.com/manual/zh/function.ini-get-all.php) - 获取所有配置选项
*   [ini\_get](http://php.p2hp.com/manual/zh/function.ini-get.php) - 获取配置选项的值
*   [ini\_restore](http://php.p2hp.com/manual/zh/function.ini-restore.php) - 恢复配置选项的值
*   [ini\_set](http://php.p2hp.com/manual/zh/function.ini-set.php) - 设置配置选项的值
*   [magic\_quotes\_runtime](http://php.p2hp.com/manual/zh/function.magic-quotes-runtime.php) - set\_magic\_quotes\_runtime的别名
*   [main](http://php.p2hp.com/manual/zh/function.main.php) - Dummy for main
*   [memory\_get\_peak\_usage](http://php.p2hp.com/manual/zh/function.memory-get-peak-usage.php) - 返回PHP分配的内存峰值
*   [memory\_get\_usage](http://php.p2hp.com/manual/zh/function.memory-get-usage.php) - 返回分配给PHP的内存量
*   [php\_ini\_loaded\_file](http://php.p2hp.com/manual/zh/function.php-ini-loaded-file.php) - 检索加载的php.ini文件的路径
*   [php\_ini\_scanned\_files](http://php.p2hp.com/manual/zh/function.php-ini-scanned-files.php) - 返回从附加的ini目录解析的.ini文件列表
*   [php\_sapi\_name](http://php.p2hp.com/manual/zh/function.php-sapi-name.php) - 返回Web服务器和PHP之间的接口类型
*   [php\_uname](http://php.p2hp.com/manual/zh/function.php-uname.php) - 返回有关运行PHP的操作系统的信息
*   [phpcredits](http://php.p2hp.com/manual/zh/function.phpcredits.php) - 打印PHP的学分
*   [phpinfo](http://php.p2hp.com/manual/zh/function.phpinfo.php) - 输出有关PHP配置的信息
*   [phpversion](http://php.p2hp.com/manual/zh/function.phpversion.php) - 获取当前的PHP版本
*   [putenv](http://php.p2hp.com/manual/zh/function.putenv.php) - 设置环境变量的值
*   [restore\_include\_path](http://php.p2hp.com/manual/zh/function.restore-include-path.php) - 恢复include\_path配置选项的值
*   [set\_include\_path](http://php.p2hp.com/manual/zh/function.set-include-path.php) - 设置include\_path配置选项
*   [set\_time\_limit](http://php.p2hp.com/manual/zh/function.set-time-limit.php) - 限制最长执行时间
*   [sys\_get\_temp\_dir](http://php.p2hp.com/manual/zh/function.sys-get-temp-dir.php) - 返回用于临时文件的目录路径
*   [version\_compare](http://php.p2hp.com/manual/zh/function.version-compare.php) - 比较两个“PHP标准化”版本号字符串
*   [zend\_thread\_id](http://php.p2hp.com/manual/zh/function.zend-thread-id.php) - 返回当前线程的唯一标识符
*   [zend\_version](http://php.p2hp.com/manual/zh/function.zend-version.php) - 获取当前Zend引擎的版本

  

错误处理
----

  

*   [debug\_backtrace](http://php.p2hp.com/manual/zh/function.debug-backtrace.php) - 生成回溯
*   [debug\_print\_backtrace](http://php.p2hp.com/manual/zh/function.debug-print-backtrace.php) - 打印回溯
*   [error\_clear\_last](http://php.p2hp.com/manual/zh/function.error-clear-last.php) - 清除最近的错误
*   [error\_get\_last](http://php.p2hp.com/manual/zh/function.error-get-last.php) - 获取上次发生的错误
*   [error\_log](http://php.p2hp.com/manual/zh/function.error-log.php) - 向定义的错误处理例程发送错误消息
*   [error\_reporting](http://php.p2hp.com/manual/zh/function.error-reporting.php) - 设置报告的PHP错误
*   [restore\_error\_handler](http://php.p2hp.com/manual/zh/function.restore-error-handler.php) - 恢复先前的错误处理函数
*   [restore\_exception\_handler](http://php.p2hp.com/manual/zh/function.restore-exception-handler.php) - 恢复先前定义的异常处理函数
*   [set\_error\_handler](http://php.p2hp.com/manual/zh/function.set-error-handler.php) - 设置用户定义的错误处理函数
*   [set\_exception\_handler](http://php.p2hp.com/manual/zh/function.set-exception-handler.php) - 设置用户定义的异常处理函数
*   [trigger\_error](http://php.p2hp.com/manual/zh/function.trigger-error.php) - 生成用户级错误/警告/通知消息
*   [user\_error](http://php.p2hp.com/manual/zh/function.user-error.php) - trigger\_error的别名

  

输出缓冲控制
------

  

*   [flush](http://php.p2hp.com/manual/zh/function.flush.php) - 刷新系统输出缓冲区
*   [ob\_clean](http://php.p2hp.com/manual/zh/function.ob-clean.php) - 清除(擦除)输出缓冲区
*   [ob\_end\_clean](http://php.p2hp.com/manual/zh/function.ob-end-clean.php) - 清除(擦除)输出缓冲区并关闭输出缓冲
*   [ob\_end\_flush](http://php.p2hp.com/manual/zh/function.ob-end-flush.php) - 刷新(发送)输出缓冲区并关闭输出缓冲
*   [ob\_flush](http://php.p2hp.com/manual/zh/function.ob-flush.php) - 刷新(发送)输出缓冲区
*   [ob\_get\_clean](http://php.p2hp.com/manual/zh/function.ob-get-clean.php) - 获取当前缓冲区内容并删除当前输出缓冲区
*   [ob\_get\_contents](http://php.p2hp.com/manual/zh/function.ob-get-contents.php) - 返回输出缓冲区的内容
*   [ob\_get\_flush](http://php.p2hp.com/manual/zh/function.ob-get-flush.php) - 刷新输出缓冲区，将其作为字符串返回并关闭输出缓冲
*   [ob\_get\_length](http://php.p2hp.com/manual/zh/function.ob-get-length.php) - 返回输出缓冲区的长度
*   [ob\_get\_level](http://php.p2hp.com/manual/zh/function.ob-get-level.php) - 返回输出缓冲机制的嵌套级别
*   [ob\_get\_status](http://php.p2hp.com/manual/zh/function.ob-get-status.php) - 获取输出缓冲区的状态
*   [ob\_gzhandler](http://php.p2hp.com/manual/zh/function.ob-gzhandler.php) - ob\_start对gzip输出缓冲区的回调函数
*   [ob\_implicit\_flush](http://php.p2hp.com/manual/zh/function.ob-implicit-flush.php) - 打开/关闭隐式刷新
*   [ob\_list\_handlers](http://php.p2hp.com/manual/zh/function.ob-list-handlers.php) - 列出正在使用的所有输出处理程序
*   [ob\_start](http://php.p2hp.com/manual/zh/function.ob-start.php) - 打开输出缓冲
*   [output\_add\_rewrite\_var](http://php.p2hp.com/manual/zh/function.output-add-rewrite-var.php) - 添加URL重写器值
*   [output\_reset\_rewrite\_vars](http://php.p2hp.com/manual/zh/function.output-reset-rewrite-vars.php) - 重置URL重写器值

  

密码散列算法
------

  

*   [password\_algos](https://php.p2hp.com/manual/zh/function.password-algos.php) - 得到可用密码散列算法id
*   [password\_get\_info](http://php.p2hp.com/manual/zh/function.password-get-info.php) - 返回有关给定哈希的信息
*   [password\_hash](http://php.p2hp.com/manual/zh/function.password-hash.php) - 创建密码哈希
*   [password\_needs\_rehash](http://php.p2hp.com/manual/zh/function.password-needs-rehash.php) - 检查给定的哈希值是否与给定的选项匹配
*   [password\_verify](http://php.p2hp.com/manual/zh/function.password-verify.php) - 验证密码是否与哈希匹配

  

会话Session
---------

  

*   [session\_abort](http://php.p2hp.com/manual/zh/function.session-abort.php) - 放弃会话数组更改并完成会话
*   [session\_cache\_expire](http://php.p2hp.com/manual/zh/function.session-cache-expire.php) - 返回当前缓存过期
*   [session\_cache\_limiter](http://php.p2hp.com/manual/zh/function.session-cache-limiter.php) - 获取和/或设置当前缓存限制器
*   [session\_commit](http://php.p2hp.com/manual/zh/function.session-commit.php) - session\_write\_close的别名
*   [session\_create\_id](http://php.p2hp.com/manual/zh/function.session-create-id.php) - 创建新的会话ID
*   [session\_decode](http://php.p2hp.com/manual/zh/function.session-decode.php) - 从会话编码的字符串中解码会话数据
*   [session\_destroy](http://php.p2hp.com/manual/zh/function.session-destroy.php) - 销毁注册到会话的所有数据
*   [session\_encode](http://php.p2hp.com/manual/zh/function.session-encode.php) - 将当前会话数据编码为会话编码字符串
*   [session\_gc](http://php.p2hp.com/manual/zh/function.session-gc.php) - 执行会话数据垃圾回收
*   [session\_get\_cookie\_params](http://php.p2hp.com/manual/zh/function.session-get-cookie-params.php) - 获取会话cookie参数
*   [session\_id](http://php.p2hp.com/manual/zh/function.session-id.php) - 获取和/或设置当前会话ID
*   [session\_is\_registered](http://php.p2hp.com/manual/zh/function.session-is-registered.php) - 查明是否在会话中注册了全局变量
*   [session\_module\_name](http://php.p2hp.com/manual/zh/function.session-module-name.php) - 获取和/或设置当前会话模块
*   [session\_name](http://php.p2hp.com/manual/zh/function.session-name.php) - 获取和/或设置当前会话名称
*   [session\_regenerate\_id](http://php.p2hp.com/manual/zh/function.session-regenerate-id.php) - 使用新生成的会话ID更新当前会话ID
*   [session\_register\_shutdown](http://php.p2hp.com/manual/zh/function.session-register-shutdown.php) - 会话关闭功能
*   [session\_register](http://php.p2hp.com/manual/zh/function.session-register.php) - 使用当前会话注册一个或多个全局变量
*   [session\_reset](http://php.p2hp.com/manual/zh/function.session-reset.php) - 使用原始值重新初始化会话数组
*   [session\_save\_path](http://php.p2hp.com/manual/zh/function.session-save-path.php) - 获取和/或设置当前会话保存路径
*   [session\_set\_cookie\_params](http://php.p2hp.com/manual/zh/function.session-set-cookie-params.php) - 设置会话cookie参数
*   [session\_set\_save\_handler](http://php.p2hp.com/manual/zh/function.session-set-save-handler.php) - 设置用户级会话存储功能
*   [session\_start](http://php.p2hp.com/manual/zh/function.session-start.php) - 启动新会话或恢复现有会话
*   [session\_status](http://php.p2hp.com/manual/zh/function.session-status.php) - 返回当前会话状态
*   [session\_unregister](http://php.p2hp.com/manual/zh/function.session-unregister.php) - 从当前会话中取消注册全局变量
*   [session\_unset](http://php.p2hp.com/manual/zh/function.session-unset.php) - 释放所有会话变量
*   [session\_write\_close](http://php.p2hp.com/manual/zh/function.session-write-close.php) - 写入会话数据和结束会话

*   [SessionHandler](http://php.p2hp.com/manual/zh/class.sessionhandler.php) — The SessionHandler class
    *   [SessionHandler::close](http://php.p2hp.com/manual/zh/sessionhandler.close.php) — Close the session
    *   [SessionHandler::create\_sid](http://php.p2hp.com/manual/zh/sessionhandler.create-sid.php) — Return a new session ID
    *   [SessionHandler::destroy](http://php.p2hp.com/manual/zh/sessionhandler.destroy.php) — Destroy a session
    *   [SessionHandler::gc](http://php.p2hp.com/manual/zh/sessionhandler.gc.php) — Cleanup old sessions
    *   [SessionHandler::open](http://php.p2hp.com/manual/zh/sessionhandler.open.php) — Initialize session
    *   [SessionHandler::read](http://php.p2hp.com/manual/zh/sessionhandler.read.php) — Read session data
    *   [SessionHandler::write](http://php.p2hp.com/manual/zh/sessionhandler.write.php) — Write session data
*   [SessionHandlerInterface](http://php.p2hp.com/manual/zh/class.sessionhandlerinterface.php) — The SessionHandlerInterface class
    *   [SessionHandlerInterface::close](http://php.p2hp.com/manual/zh/sessionhandlerinterface.close.php) — Close the session
    *   [SessionHandlerInterface::destroy](http://php.p2hp.com/manual/zh/sessionhandlerinterface.destroy.php) — Destroy a session
    *   [SessionHandlerInterface::gc](http://php.p2hp.com/manual/zh/sessionhandlerinterface.gc.php) — Cleanup old sessions
    *   [SessionHandlerInterface::open](http://php.p2hp.com/manual/zh/sessionhandlerinterface.open.php) — Initialize session
    *   [SessionHandlerInterface::read](http://php.p2hp.com/manual/zh/sessionhandlerinterface.read.php) — Read session data
    *   [SessionHandlerInterface::write](http://php.p2hp.com/manual/zh/sessionhandlerinterface.write.php) — Write session data
*   [SessionIdInterface](http://php.p2hp.com/manual/zh/class.sessionidinterface.php) — The SessionIdInterface interface
    *   [SessionIdInterface::create\_sid](http://php.p2hp.com/manual/zh/sessionidinterface.create-sid.php) — Create session ID
*   [SessionUpdateTimestampHandlerInterface](http://php.p2hp.com/manual/zh/class.sessionupdatetimestamphandlerinterface.php) — The SessionUpdateTimestampHandlerInterface interface
    *   [SessionUpdateTimestampHandlerInterface::updateTimestamp](http://php.p2hp.com/manual/zh/sessionupdatetimestamphandlerinterface.updatetimestamp.php) — Update timestamp
    *   [SessionUpdateTimestampHandlerInterface::validateId](http://php.p2hp.com/manual/zh/sessionupdatetimestamphandlerinterface.validateid.php) — Validate ID


CSPRNG伪随机数产生器
-------------

  

*   [random\_bytes](http://php.p2hp.com/manual/zh/function.random-bytes.php) - 生成加密安全的伪随机字节
*   [random\_int](http://php.p2hp.com/manual/zh/function.random-int.php) - 激活加密安全伪随机整数

  

JSON
----


*   [JsonException](http://php.p2hp.com/manual/zh/class.jsonexception.php) — The JsonException class
*   [JsonSerializable](http://php.p2hp.com/manual/zh/class.jsonserializable.php) — JSON 序列化接口
    *   [JsonSerializable::jsonSerialize](http://php.p2hp.com/manual/zh/jsonserializable.jsonserialize.php) — 指定需要被序列化成 JSON 的数据
*   [JSON 函数](#)
    *   [json\_decode](http://php.p2hp.com/manual/zh/function.json-decode.php) - 解码JSON字符串
    *   [json\_encode](http://php.p2hp.com/manual/zh/function.json-encode.php) - 返回值的JSON表示形式
    *   [json\_last\_error\_msg](http://php.p2hp.com/manual/zh/function.json-last-error-msg.php) - 返回最后一个json\_encode()或json\_decode()调用的错误字符串
    *   [json\_last\_error](http://php.p2hp.com/manual/zh/function.json-last-error.php) - 返回上次发生的错误


Stream[(more)](https://php.p2hp.com/manual/zh/book.stream.php)
--------------------------------------------------------------

  

*   [stream\_bucket\_append](http://php.p2hp.com/manual/zh/function.stream-bucket-append.php) - 将存储桶附加到旅
*   [stream\_bucket\_make\_writeable](http://php.p2hp.com/manual/zh/function.stream-bucket-make-writeable.php) - 从旅中返回一个桶对象进行操作
*   [stream\_bucket\_new](http://php.p2hp.com/manual/zh/function.stream-bucket-new.php) - 创建一个用于当前流的新存储桶
*   [stream\_bucket\_prepend](http://php.p2hp.com/manual/zh/function.stream-bucket-prepend.php) - 将存储桶前置到旅
*   [stream\_context\_create](http://php.p2hp.com/manual/zh/function.stream-context-create.php) - 创建流上下文
*   [stream\_context\_get\_default](http://php.p2hp.com/manual/zh/function.stream-context-get-default.php) - 检索默认流上下文
*   [stream\_context\_get\_options](http://php.p2hp.com/manual/zh/function.stream-context-get-options.php) - 检索流/包装器/上下文的选项
*   [stream\_context\_get\_params](http://php.p2hp.com/manual/zh/function.stream-context-get-params.php) - 从上下文中检索参数
*   [stream\_context\_set\_default](http://php.p2hp.com/manual/zh/function.stream-context-set-default.php) - 设置默认流上下文
*   [stream\_context\_set\_option](http://php.p2hp.com/manual/zh/function.stream-context-set-option.php) - 为流/包装器/上下文设置选项
*   [stream\_context\_set\_params](http://php.p2hp.com/manual/zh/function.stream-context-set-params.php) - 设置流/包装器/上下文的参数
*   [stream\_copy\_to\_stream](http://php.p2hp.com/manual/zh/function.stream-copy-to-stream.php) - 将数据从一个流复制到另一个流
*   [stream\_filter\_append](http://php.p2hp.com/manual/zh/function.stream-filter-append.php) - 将过滤器附加到流
*   [stream\_filter\_prepend](http://php.p2hp.com/manual/zh/function.stream-filter-prepend.php) - 将过滤器附加到流
*   [stream\_filter\_register](http://php.p2hp.com/manual/zh/function.stream-filter-register.php) - 注册用户定义的流过滤器
*   [stream\_filter\_remove](http://php.p2hp.com/manual/zh/function.stream-filter-remove.php) - 从流中删除过滤器
*   [stream\_get\_contents](http://php.p2hp.com/manual/zh/function.stream-get-contents.php) - 将流的剩余部分读入字符串
*   [stream\_get\_filters](http://php.p2hp.com/manual/zh/function.stream-get-filters.php) - 检索已注册过滤器的列表
*   [stream\_get\_line](http://php.p2hp.com/manual/zh/function.stream-get-line.php) - 从流资源获取直到给定分隔符的行
*   [stream\_get\_meta\_data](http://php.p2hp.com/manual/zh/function.stream-get-meta-data.php) - 从流/文件指针中检索标头/元数据
*   [stream\_get\_transports](http://php.p2hp.com/manual/zh/function.stream-get-transports.php) - 检索已注册套接字传输的列表
*   [stream\_get\_wrappers](http://php.p2hp.com/manual/zh/function.stream-get-wrappers.php) - 检索已注册流的列表
*   [stream\_is\_local](http://php.p2hp.com/manual/zh/function.stream-is-local.php) - 检查流是否是本地流
*   [stream\_isatty](http://php.p2hp.com/manual/zh/function.stream-isatty.php) - 检查流是否为TTY
*   [stream\_notification\_callback](http://php.p2hp.com/manual/zh/function.stream-notification-callback.php) - 通知上下文参数的回调函数
*   [stream\_register\_wrapper](http://php.p2hp.com/manual/zh/function.stream-register-wrapper.php) - stream\_wrapper\_register的别名
*   [stream\_resolve\_include\_path](http://php.p2hp.com/manual/zh/function.stream-resolve-include-path.php) - 根据包含路径解析文件名
*   [stream\_select](http://php.p2hp.com/manual/zh/function.stream-select.php) - 在给定的流数组上运行select()系统调用的等价物，并使用tv\_sec和tv\_usec指定的超时
*   [stream\_set\_blocking](http://php.p2hp.com/manual/zh/function.stream-set-blocking.php) - 在流上设置阻塞/非阻塞模式
*   [stream\_set\_chunk\_size](http://php.p2hp.com/manual/zh/function.stream-set-chunk-size.php) - 设置流块大小
*   [stream\_set\_read\_buffer](http://php.p2hp.com/manual/zh/function.stream-set-read-buffer.php) - 在给定流上设置读取文件缓冲
*   [stream\_set\_timeout](http://php.p2hp.com/manual/zh/function.stream-set-timeout.php) - 在流上设置超时时间
*   [stream\_set\_write\_buffer](http://php.p2hp.com/manual/zh/function.stream-set-write-buffer.php) - 设置给定流上的写文件缓冲
*   [stream\_socket\_accept](http://php.p2hp.com/manual/zh/function.stream-socket-accept.php) - 接受stream\_socket\_server创建的套接字上的连接
*   [stream\_socket\_client](http://php.p2hp.com/manual/zh/function.stream-socket-client.php) - 打开Internet或Unix域套接字连接
*   [stream\_socket\_enable\_crypto](http://php.p2hp.com/manual/zh/function.stream-socket-enable-crypto.php) - 在已连接的套接字上打开/关闭加密
*   [stream\_socket\_get\_name](http://php.p2hp.com/manual/zh/function.stream-socket-get-name.php) - 检索本地或远程套接字的名称
*   [stream\_socket\_pair](http://php.p2hp.com/manual/zh/function.stream-socket-pair.php) - 创建一对连接的，无法区分的套接字流
*   [stream\_socket\_recvfrom](http://php.p2hp.com/manual/zh/function.stream-socket-recvfrom.php) - 从连接或不连接的套接字接收数据
*   [stream\_socket\_sendto](http://php.p2hp.com/manual/zh/function.stream-socket-sendto.php) - 向套接字发送消息，无论它是否已连接
*   [stream\_socket\_server](http://php.p2hp.com/manual/zh/function.stream-socket-server.php) - 创建Internet或Unix域服务器套接字
*   [stream\_socket\_shutdown](http://php.p2hp.com/manual/zh/function.stream-socket-shutdown.php) - 关闭全双工连接
*   [stream\_supports\_lock](http://php.p2hp.com/manual/zh/function.stream-supports-lock.php) - 判断流是否支持锁定
*   [stream\_wrapper\_register](http://php.p2hp.com/manual/zh/function.stream-wrapper-register.php) - 注册实现为PHP类的URL包装器
*   [stream\_wrapper\_restore](http://php.p2hp.com/manual/zh/function.stream-wrapper-restore.php) - 恢复以前未注册的内置包装器
*   [stream\_wrapper\_unregister](http://php.p2hp.com/manual/zh/function.stream-wrapper-unregister.php) - 取消注册URL包装器

  

SPL[(more)](https://php.p2hp.com/manual/zh/book.spl.php)
--------------------------------------------------------

  

*   [class\_implements](http://php.p2hp.com/manual/zh/function.class-implements.php) - 返回由给定类或接口实现的接口
*   [class\_parents](http://php.p2hp.com/manual/zh/function.class-parents.php) - 返回给定类的父类
*   [class\_uses](http://php.p2hp.com/manual/zh/function.class-uses.php) - 返回给定类使用的特征
*   [iterator\_apply](http://php.p2hp.com/manual/zh/function.iterator-apply.php) - 为迭代器中的每个元素调用一个函数
*   [iterator\_count](http://php.p2hp.com/manual/zh/function.iterator-count.php) - 计算迭代器中的元素
*   [iterator\_to\_array](http://php.p2hp.com/manual/zh/function.iterator-to-array.php) - 将迭代器复制到数组中
*   [spl\_autoload\_call](http://php.p2hp.com/manual/zh/function.spl-autoload-call.php) - 尝试所有已注册的\_\_autoload()函数来加载请求的类
*   [spl\_autoload\_extensions](http://php.p2hp.com/manual/zh/function.spl-autoload-extensions.php) - 注册并返回spl\_autoload的默认文件扩展名
*   [spl\_autoload\_functions](http://php.p2hp.com/manual/zh/function.spl-autoload-functions.php) - 返回所有已注册的\_\_autoload()函数
*   [spl\_autoload\_register](http://php.p2hp.com/manual/zh/function.spl-autoload-register.php) - 将给定函数注册为\_\_autoload()实现
*   [spl\_autoload\_unregister](http://php.p2hp.com/manual/zh/function.spl-autoload-unregister.php) - 取消注册给定函数作为\_\_autoload()实现
*   [spl\_autoload](http://php.p2hp.com/manual/zh/function.spl-autoload.php) - \_\_autoload()的默认实现
*   [spl\_classes](http://php.p2hp.com/manual/zh/function.spl-classes.php) - 返回可用的SPL类
*   [spl\_object\_hash](http://php.p2hp.com/manual/zh/function.spl-object-hash.php) - 返回给定对象的哈希id
*   [spl\_object\_id](http://php.p2hp.com/manual/zh/function.spl-object-id.php) - 返回给定对象的整数对象句柄

  

BCMath
------

  

*   [bcadd](http://php.p2hp.com/manual/zh/function.bcadd.php) - 添加两个任意精度数字
*   [bccomp](http://php.p2hp.com/manual/zh/function.bccomp.php) - 比较两个任意精度数
*   [bcdiv](http://php.p2hp.com/manual/zh/function.bcdiv.php) - 除以两个任意精度数
*   [bcmod](http://php.p2hp.com/manual/zh/function.bcmod.php) - 获取任意精度数的模数
*   [bcmul](http://php.p2hp.com/manual/zh/function.bcmul.php) - 将两个任意精度数相乘
*   [bcpow](http://php.p2hp.com/manual/zh/function.bcpow.php) - 将任意精度数字提升到另一个
*   [bcpowmod](http://php.p2hp.com/manual/zh/function.bcpowmod.php) - 将任意精度数提升到另一个，减去指定的模数
*   [bcscale](http://php.p2hp.com/manual/zh/function.bcscale.php) - 为所有bc数学函数设置或获取默认缩放参数
*   [bcsqrt](http://php.p2hp.com/manual/zh/function.bcsqrt.php) - 获取任意精度数的平方根
*   [bcsub](http://php.p2hp.com/manual/zh/function.bcsub.php) - 从另一个中减去一个任意精度数

  

杂项
--

  

*   [connection\_aborted](http://php.p2hp.com/manual/zh/function.connection-aborted.php) - 检查客户端是否已断开连接
*   [connection\_status](http://php.p2hp.com/manual/zh/function.connection-status.php) - 返回连接状态位域
*   [constant](http://php.p2hp.com/manual/zh/function.constant.php) - 返回常量的值
*   [define](http://php.p2hp.com/manual/zh/function.define.php) - 定义命名常量
*   [defined](http://php.p2hp.com/manual/zh/function.defined.php) - 检查给定的命名常量是否存在
*   [die](http://php.p2hp.com/manual/zh/function.die.php) - 相当于退出
*   [eval](http://php.p2hp.com/manual/zh/function.eval.php) - 将字符串评估为PHP代码
*   [exit](http://php.p2hp.com/manual/zh/function.exit.php) - 输出消息并终止当前脚本
*   [get\_browser](http://php.p2hp.com/manual/zh/function.get-browser.php) - 告诉用户的浏览器能够做什么
*   [\_\_halt\_compiler](http://php.p2hp.com/manual/zh/function.halt-compiler.php) - 暂停编译器执行
*   [highlight\_file](http://php.p2hp.com/manual/zh/function.highlight-file.php) - 突出显示文件的语法
*   [highlight\_string](http://php.p2hp.com/manual/zh/function.highlight-string.php) - 突出显示字符串的语法
*   [hrtime](http://php.p2hp.com/manual/zh/function.hrtime.php) - 获取系统的高分辨率时间
*   [ignore\_user\_abort](http://php.p2hp.com/manual/zh/function.ignore-user-abort.php) - 设置客户端断开连接是否应中止脚本执行
*   [pack](http://php.p2hp.com/manual/zh/function.pack.php) - 将数据打包成二进制字符串
*   [php\_check\_syntax](http://php.p2hp.com/manual/zh/function.php-check-syntax.php) - 检查(并执行)指定文件的PHP语法
*   [php\_strip\_whitespace](http://php.p2hp.com/manual/zh/function.php-strip-whitespace.php) - 返回带有剥离注释和空格的源代码
*   [sapi\_windows\_cp\_conv](http://php.p2hp.com/manual/zh/function.sapi-windows-cp-conv.php) - 将字符串从一个代码页转换为另一个代码页
*   [sapi\_windows\_cp\_get](http://php.p2hp.com/manual/zh/function.sapi-windows-cp-get.php) - 获取流程代码页
*   [sapi\_windows\_cp\_is\_utf8](http://php.p2hp.com/manual/zh/function.sapi-windows-cp-is-utf8.php) - 指示代码页是否与UTF-8兼容
*   [sapi\_windows\_cp\_set](http://php.p2hp.com/manual/zh/function.sapi-windows-cp-set.php) - 设置进程代码页
*   [sapi\_windows\_set\_ctrl\_handler](https://php.p2hp.com/manual/zh/function.sapi-windows-set-ctrl-handler.php) - 设置或删除一个CTRL事件处理程序
*   [sapi\_windows\_vt100\_support](http://php.p2hp.com/manual/zh/function.sapi-windows-vt100-support.php) - 为与Windows控制台的输出缓冲区关联的指定流获取或设置VT100支持。
*   [show\_source](http://php.p2hp.com/manual/zh/function.show-source.php) - highlight\_file的别名
*   [sleep](http://php.p2hp.com/manual/zh/function.sleep.php) - 延迟执行
*   [sys\_getloadavg](http://php.p2hp.com/manual/zh/function.sys-getloadavg.php) - 获取系统平均负载
*   [time\_nanosleep](http://php.p2hp.com/manual/zh/function.time-nanosleep.php) - 延迟数秒和纳秒
*   [time\_sleep\_until](http://php.p2hp.com/manual/zh/function.time-sleep-until.php) - 使脚本休眠直到指定的时间
*   [uniqid](http://php.p2hp.com/manual/zh/function.uniqid.php) - 生成唯一ID
*   [unpack](http://php.p2hp.com/manual/zh/function.unpack.php) - 从二进制字符串中解压缩数据
*   [usleep](http://php.p2hp.com/manual/zh/function.usleep.php) - 以微秒为单位延迟执行

  

Hash
----

  

*   [hash\_algos](http://php.p2hp.com/manual/zh/function.hash-algos.php) - 返回已注册的散列算法列表
*   [hash\_copy](http://php.p2hp.com/manual/zh/function.hash-copy.php) - 复制散列上下文
*   [hash\_equals](http://php.p2hp.com/manual/zh/function.hash-equals.php) - 定时攻击安全字符串比较
*   [hash\_file](http://php.p2hp.com/manual/zh/function.hash-file.php) - 使用给定文件的内容生成哈希值
*   [hash\_final](http://php.p2hp.com/manual/zh/function.hash-final.php) - 完成增量散列并返回结果摘要
*   [hash\_hkdf](http://php.p2hp.com/manual/zh/function.hash-hkdf.php) - 生成提供的键输入的HKDF键派生
*   [hash\_hmac\_algos](http://php.p2hp.com/manual/zh/function.hash-hmac-algos.php) - 返回适用于hash\_hmac的已注册散列算法列表
*   [hash\_hmac\_file](http://php.p2hp.com/manual/zh/function.hash-hmac-file.php) - 使用HMAC方法和给定文件的内容生成键控哈希值
*   [hash\_hmac](http://php.p2hp.com/manual/zh/function.hash-hmac.php) - 使用HMAC方法生成键控哈希值
*   [hash\_init](http://php.p2hp.com/manual/zh/function.hash-init.php) - 初始化增量散列上下文
*   [hash\_pbkdf2](http://php.p2hp.com/manual/zh/function.hash-pbkdf2.php) - 生成提供的密码的PBKDF2密钥派生
*   [hash\_update\_file](http://php.p2hp.com/manual/zh/function.hash-update-file.php) - 将数据从文件泵入活动的哈希上下文
*   [hash\_update\_stream](http://php.p2hp.com/manual/zh/function.hash-update-stream.php) - 从打开的流中将数据泵入活动的哈希上下文
*   [hash\_update](http://php.p2hp.com/manual/zh/function.hash-update.php) - 将数据泵入活动的哈希上下文
*   [hash](http://php.p2hp.com/manual/zh/function.hash.php) - 生成哈希值(消息摘要)

  

PDO
---


PDO - PDO类

*   [PDO::beginTransaction](http://php.p2hp.com/manual/zh/pdo.begintransaction.php) - 启动事务
*   [PDO::commit](http://php.p2hp.com/manual/zh/pdo.commit.php) - 提交事务
*   [PDO::\_\_ construct](http://php.p2hp.com/manual/zh/pdo.construct.php) - 创建表示与数据库的连接的PDO实例
*   [PDO::errorCode](http://php.p2hp.com/manual/zh/pdo.errorcode.php) - 获取与数据库句柄上的最后一个操作关联的SQLSTATE
*   [PDO::errorInfo](http://php.p2hp.com/manual/zh/pdo.errorinfo.php) - 获取与数据库句柄上的最后一个操作关联的扩展错误信息
*   [PDO::exec](http://php.p2hp.com/manual/zh/pdo.exec.php) - 执行SQL语句并返回受影响的行数
*   [PDO::getAttribute](http://php.p2hp.com/manual/zh/pdo.getattribute.php) - 检索数据库连接属性
*   [PDO::getAvailableDrivers](http://php.p2hp.com/manual/zh/pdo.getavailabledrivers.php) - 返回可用PDO驱动程序的数组
*   [PDO::inTransaction](http://php.p2hp.com/manual/zh/pdo.intransaction.php) - 检查是否在事务内部
*   [PDO::lastInsertId](http://php.p2hp.com/manual/zh/pdo.lastinsertid.php) - 返回最后插入的行或序列值的ID
*   [PDO::prepare](http://php.p2hp.com/manual/zh/pdo.prepare.php) - 准备要执行的语句并返回一个语句对象
*   [PDO::query](http://php.p2hp.com/manual/zh/pdo.query.php) - 执行SQL语句，将结果集作为PDOStatement对象返回
*   [PDO::quote](http://php.p2hp.com/manual/zh/pdo.quote.php) - 引用用于查询的字符串
*   [PDO::rollBack](http://php.p2hp.com/manual/zh/pdo.rollback.php) - 回滚事务
*   [PDO::setAttribute](http://php.p2hp.com/manual/zh/pdo.setattribute.php) - 设置属性

PDOStatement - PDOStatement类

*   [PDOStatement::bindColumn](http://php.p2hp.com/manual/zh/pdostatement.bindcolumn.php) - 将列绑定到PHP变量
*   [PDOStatement::bindParam](http://php.p2hp.com/manual/zh/pdostatement.bindparam.php) - 将参数绑定到指定的变量名称
*   [PDOStatement::bindValue](http://php.p2hp.com/manual/zh/pdostatement.bindvalue.php) - 将值绑定到参数
*   [PDOStatement::closeCursor](http://php.p2hp.com/manual/zh/pdostatement.closecursor.php) - 关闭游标，使语句再次执行
*   [PDOStatement::columnCount](http://php.p2hp.com/manual/zh/pdostatement.columncount.php) - 返回结果集中的列数
*   [PDOStatement::debugDumpParams](http://php.p2hp.com/manual/zh/pdostatement.debugdumpparams.php) - 转储SQL准备的命令
*   [PDOStatement::errorCode](http://php.p2hp.com/manual/zh/pdostatement.errorcode.php) - 获取与语句句柄上的最后一个操作关联的SQLSTATE
*   [PDOStatement::errorInfo](http://php.p2hp.com/manual/zh/pdostatement.errorinfo.php) - 获取与语句句柄上的最后一个操作关联的扩展错误信息
*   [PDOStatement::execute](http://php.p2hp.com/manual/zh/pdostatement.execute.php) - 执行预准备语句
*   [PDOStatement::fetch](http://php.p2hp.com/manual/zh/pdostatement.fetch.php) - 从结果集中获取下一行
*   [PDOStatement::fetchAll](http://php.p2hp.com/manual/zh/pdostatement.fetchall.php) - 返回包含所有结果集行的数组
*   [PDOStatement::fetchColumn](http://php.p2hp.com/manual/zh/pdostatement.fetchcolumn.php) - 从结果集的下一行返回单个列
*   [PDOStatement::fetchObject](http://php.p2hp.com/manual/zh/pdostatement.fetchobject.php) - 获取下一行并将其作为对象返回
*   [PDOStatement::getAttribute](http://php.p2hp.com/manual/zh/pdostatement.getattribute.php) - 检索语句属性
*   [PDOStatement::getColumnMeta](http://php.p2hp.com/manual/zh/pdostatement.getcolumnmeta.php) - 返回结果集中列的元数据
*   [PDOStatement::nextRowset](http://php.p2hp.com/manual/zh/pdostatement.nextrowset.php) - 前进到多行集语句句柄中的下一个行集
*   [PDOStatement::rowCount](http://php.p2hp.com/manual/zh/pdostatement.rowcount.php) - 返回受上一个SQL语句影响的行数
*   [PDOStatement::setAttribute](http://php.p2hp.com/manual/zh/pdostatement.setattribute.php) - 设置语句属性
*   [PDOStatement::setFetchMode](http://php.p2hp.com/manual/zh/pdostatement.setfetchmode.php) - 设置此语句的默认提取模式

*   [PDOException](http://php.p2hp.com/manual/zh/class.pdoexception.php) — PDOException 异常类


MySQLi
------


mysqli - mysqli类  

*   [mysqli::$affected\_rows](http://php.p2hp.com/manual/zh/mysqli.affected-rows.php) - (mysqli\_affected\_rows)获取先前MySQL操作中受影响的行数
*   [mysqli::autocommit](http://php.p2hp.com/manual/zh/mysqli.autocommit.php) - (mysqli\_autocommit)打开或关闭自动提交数据库修改
*   [mysqli::begin\_transaction](http://php.p2hp.com/manual/zh/mysqli.begin-transaction.php) - (mysqli\_begin\_transaction)启动一个事务
*   [mysqli::change\_user](http://php.p2hp.com/manual/zh/mysqli.change-user.php) - (mysqli\_change\_user)更改指定数据库连接的用户
*   [mysqli::character\_set\_name](http://php.p2hp.com/manual/zh/mysqli.character-set-name.php) - (mysqli\_character\_set\_name)返回数据库连接的默认字符集
*   [mysqli::close](http://php.p2hp.com/manual/zh/mysqli.close.php) - (mysqli\_close)关闭以前打开的数据库连接
*   [mysqli::commit](http://php.p2hp.com/manual/zh/mysqli.commit.php) - (mysqli\_commit)提交当前事务
*   [mysqli::$connect\_errno](http://php.p2hp.com/manual/zh/mysqli.connect-errno.php) - (mysqli\_connect\_errno) 返回上次连接调用的错误代码
*   [mysqli::$connect\_error](http://php.p2hp.com/manual/zh/mysqli.connect-error.php) - (mysqli\_connect\_error)返回上次连接错误的字符串描述
*   [mysqli::\_\_ construct](http://php.p2hp.com/manual/zh/mysqli.construct.php) - (mysqli\_connect)打开与MySQL服务器的新连接
*   [mysqli::debug](http://php.p2hp.com/manual/zh/mysqli.debug.php) - (mysqli\_debug)执行调试操作
*   [mysqli::dump\_debug\_info](http://php.p2hp.com/manual/zh/mysqli.dump-debug-info.php) - (mysqli\_dump\_debug\_info)将调试信息转储到日志中
*   [mysqli::$errno](http://php.p2hp.com/manual/zh/mysqli.errno.php) - (mysqli\_errno)返回最近函数调用的错误代码
*   [mysqli::$error\_list](http://php.p2hp.com/manual/zh/mysqli.error-list.php) - (mysqli\_error\_list)返回上一个执行命令的错误列表
*   [mysqli::$error](http://php.p2hp.com/manual/zh/mysqli.error.php) - (mysqli\_error)返回上一个错误的字符串描述
*   [mysqli::$field\_count](http://php.p2hp.com/manual/zh/mysqli.field-count.php) - (mysqli\_field\_count)返回最近查询的列数
*   [mysqli::get\_charset](http://php.p2hp.com/manual/zh/mysqli.get-charset.php) - (mysqli\_get\_charset)返回一个字符集对象
*   [mysqli::$client\_info](http://php.p2hp.com/manual/zh/mysqli.get-client-info.php) - (mysqli\_get\_client\_info)获取MySQL客户端信息
*   [mysqli::$client\_version](http://php.p2hp.com/manual/zh/mysqli.get-client-version.php) - (mysqli\_get\_client\_version)以整数形式返回MySQL客户端版本
*   [mysqli::get\_connection\_stats](http://php.p2hp.com/manual/zh/mysqli.get-connection-stats.php) - (mysqli\_get\_connection\_stats)返回有关客户端连接的统计信息
*   [mysqli::$host\_info](http://php.p2hp.com/manual/zh/mysqli.get-host-info.php) - (mysqli\_get\_host\_info)返回表示所用连接类型的字符串
*   [mysqli::$protocol\_version](http://php.p2hp.com/manual/zh/mysqli.get-proto-info.php) - (mysqli\_get\_proto\_info)返回使用的MySQL协议的版本
*   [mysqli::$server\_info](http://php.p2hp.com/manual/zh/mysqli.get-server-info.php) - (mysqli\_get\_server\_info)返回MySQL服务器的版本
*   [mysqli::$server\_version](http://php.p2hp.com/manual/zh/mysqli.get-server-version.php) - (mysqli\_get\_server\_version)以整数形式返回MySQL服务器的版本
*   [mysqli::get\_warnings](http://php.p2hp.com/manual/zh/mysqli.get-warnings.php) - (mysqli\_get\_warnings)获得SHOW WARNINGS的结果
*   [mysqli::$info](http://php.p2hp.com/manual/zh/mysqli.info.php) - (mysqli\_info)检索有关最近执行的查询的信息
*   [mysqli::init](http://php.p2hp.com/manual/zh/mysqli.init.php) - (mysqli\_init)初始化MySQLi并返回一个与mysqli\_real\_connect()一起使用的资源
*   [mysqli::$insert\_id](http://php.p2hp.com/manual/zh/mysqli.insert-id.php) - (mysqli\_insert\_id)返回最新查询中使用的自动生成的id
*   [mysqli::kill](http://php.p2hp.com/manual/zh/mysqli.kill.php) - (mysqli\_kill)要求服务器终止MySQL线程
*   [mysqli::more\_results](http://php.p2hp.com/manual/zh/mysqli.more-results.php) - (mysqli\_more\_results)检查多查询是否还有查询结果
*   [mysqli::multi\_query](http://php.p2hp.com/manual/zh/mysqli.multi-query.php) - (mysqli\_multi\_query)对数据库执行查询
*   [mysqli::next\_result](http://php.p2hp.com/manual/zh/mysqli.next-result.php) - (mysqli\_next\_result)从multi\_query准备下一个结果
*   [mysqli::options](http://php.p2hp.com/manual/zh/mysqli.options.php) - (mysqli\_options)设置选项
*   [mysqli::ping](http://php.p2hp.com/manual/zh/mysqli.ping.php) - (mysqli\_ping)ping服务器连接，或者如果连接断开，则尝试重新连接
*   [mysqli::poll](http://php.p2hp.com/manual/zh/mysqli.poll.php) - (mysqli\_poll)民意调查连接
*   [mysqli::prepare](http://php.p2hp.com/manual/zh/mysqli.prepare.php) - (mysqli\_prepare)准备一条SQL语句以便执行
*   [mysqli::query](http://php.p2hp.com/manual/zh/mysqli.query.php) - (mysqli\_query)对数据库执行查询
*   [mysqli::real\_connect](http://php.p2hp.com/manual/zh/mysqli.real-connect.php) - (mysqli\_real\_connect)打开与mysql服务器的连接
*   [mysqli::real\_escape\_string](http://php.p2hp.com/manual/zh/mysqli.real-escape-string.php) -(mysqli\_real\_escape\_string) 在SQL语句中使用字符串中的特殊字符转义，并考虑连接的当前字符集
*   [mysqli::real\_query](http://php.p2hp.com/manual/zh/mysqli.real-query.php) - (mysqli\_real\_query)执行SQL查询
*   [mysqli::reap\_async\_query](http://php.p2hp.com/manual/zh/mysqli.reap-async-query.php) - (mysqli\_reap\_async\_query)从异步查询中获取结果
*   [mysqli::refresh](http://php.p2hp.com/manual/zh/mysqli.refresh.php) - (mysqli\_refresh)刷新
*   [mysqli::release\_savepoint](http://php.p2hp.com/manual/zh/mysqli.release-savepoint.php) - (mysqli\_release\_savepoint)从当前事务的保存点集中删除指定的保存点
*   [mysqli::rollback](http://php.p2hp.com/manual/zh/mysqli.rollback.php) - (mysqli\_rollback)回滚当前事务
*   [mysqli::savepoint](http://php.p2hp.com/manual/zh/mysqli.savepoint.php) - (mysqli\_savepoint)设置命名的事务保存点
*   [mysqli::select\_db](http://php.p2hp.com/manual/zh/mysqli.select-db.php) - (mysqli\_select\_db)选择数据库查询的默认数据库
*   [mysqli::set\_charset](http://php.p2hp.com/manual/zh/mysqli.set-charset.php) - (mysqli\_set\_charset)设置默认客户端字符集
*   [mysqli::$sqlstate](http://php.p2hp.com/manual/zh/mysqli.sqlstate.php) - (mysqli\_sqlstate)返回先前MySQL操作的SQLSTATE错误
*   [mysqli::ssl\_set](http://php.p2hp.com/manual/zh/mysqli.ssl-set.php) - (mysqli\_ssl\_set)用于使用SSL建立安全连接
*   [mysqli::stat](http://php.p2hp.com/manual/zh/mysqli.stat.php) - (mysqli\_stat)获取当前系统状态
*   [mysqli::stmt\_init](http://php.p2hp.com/manual/zh/mysqli.stmt-init.php) - (mysqli\_stmt\_init)初始化一个语句并返回一个与mysqli\_stmt\_prepare一起使用的对象
*   [mysqli::store\_result](http://php.p2hp.com/manual/zh/mysqli.store-result.php) - (mysqli\_store\_result)从上一个查询中传输结果集
*   [mysqli::$thread\_id](http://php.p2hp.com/manual/zh/mysqli.thread-id.php) - (mysqli\_thread\_id)返回当前连接的线程ID
*   [mysqli::thread\_safe](http://php.p2hp.com/manual/zh/mysqli.thread-safe.php) - (mysqli\_thread\_safe)返回是否给出线程安全性
*   [mysqli::use\_result](http://php.p2hp.com/manual/zh/mysqli.use-result.php) - (mysqli\_use\_result)启动结果集检索
*   [mysqli::$warning\_count](http://php.p2hp.com/manual/zh/mysqli.warning-count.php) - (mysqli\_warning\_count)返回给定链接的最后一个查询的警告数

mysqli\_stmt - mysqli\_stmt类  

*   [mysqli\_stmt::$affected\_rows](http://php.p2hp.com/manual/zh/mysqli-stmt.affected-rows.php) - (mysqli\_stmt\_affected\_rows)返回上次执行的语句更改，删除或插入的总行数
*   [mysqli\_stmt::attr\_get](http://php.p2hp.com/manual/zh/mysqli-stmt.attr-get.php) - (mysqli\_stmt\_attr\_get)用于获取语句属性的当前值
*   [mysqli\_stmt::attr\_set](http://php.p2hp.com/manual/zh/mysqli-stmt.attr-set.php) - (mysqli\_stmt\_attr\_set)用于修改[预](http://php.p2hp.com/manual/zh/mysqli-stmt.attr-set.php)准备语句的行为
*   [mysqli\_stmt::bind\_param](http://php.p2hp.com/manual/zh/mysqli-stmt.bind-param.php) - (mysqli\_stmt\_bind\_param)将变量作为参数绑定到[预](http://php.p2hp.com/manual/zh/mysqli-stmt.bind-param.php)准备语句
*   [mysqli\_stmt::bind\_result](http://php.p2hp.com/manual/zh/mysqli-stmt.bind-result.php) - (mysqli\_stmt\_bind\_result)将变量绑定到结果存储的[预](http://php.p2hp.com/manual/zh/mysqli-stmt.bind-result.php)准备语句
*   [mysqli\_stmt::close](http://php.p2hp.com/manual/zh/mysqli-stmt.close.php) - (mysqli\_stmt\_close)关闭准备好的语句
*   [mysqli\_stmt::\_\_ construct](http://php.p2hp.com/manual/zh/mysqli-stmt.construct.php) - 构造一个新的mysqli\_stmt对象
*   [mysqli\_stmt::data\_seek](http://php.p2hp.com/manual/zh/mysqli-stmt.data-seek.php) - (mysqli\_stmt\_data\_seek)寻找语句结果集中的任意行
*   [mysqli\_stmt::$errno](http://php.p2hp.com/manual/zh/mysqli-stmt.errno.php) - (mysqli\_stmt\_errno)返回最近语句调用的错误代码
*   [mysqli\_stmt::$error\_list](http://php.p2hp.com/manual/zh/mysqli-stmt.error-list.php) - (mysqli\_stmt\_error\_list)返回上一个执行语句的错误列表
*   [mysqli\_stmt::$error](http://php.p2hp.com/manual/zh/mysqli-stmt.error.php) - (mysqli\_stmt\_error)返回上一个语句错误的字符串描述
*   [mysqli\_stmt::execute](http://php.p2hp.com/manual/zh/mysqli-stmt.execute.php) - (mysqli\_stmt\_execute)执行准备好的Query
*   [mysqli\_stmt::fetch](http://php.p2hp.com/manual/zh/mysqli-stmt.fetch.php) - (mysqli\_stmt\_fetch)将预准备语句的结果[提取](http://php.p2hp.com/manual/zh/mysqli-stmt.fetch.php)到绑定变量中
*   [mysqli\_stmt::$field\_count](http://php.p2hp.com/manual/zh/mysqli-stmt.field-count.php) - (mysqli\_stmt\_field\_count)返回给定语句中的字段数
*   [mysqli\_stmt::free\_result](http://php.p2hp.com/manual/zh/mysqli-stmt.free-result.php) - (mysqli\_stmt\_free\_result)释放给定语句句柄的存储结果内存
*   [mysqli\_stmt::get\_result](http://php.p2hp.com/manual/zh/mysqli-stmt.get-result.php) - (mysqli\_stmt\_get\_result)从[预](http://php.p2hp.com/manual/zh/mysqli-stmt.get-result.php)准备语句中获取结果集
*   [mysqli\_stmt::get\_warnings](http://php.p2hp.com/manual/zh/mysqli-stmt.get-warnings.php) - (mysqli\_stmt\_get\_warnings)获取SHOW WARNINGS的结果
*   [mysqli\_stmt::$insert\_id](http://php.p2hp.com/manual/zh/mysqli-stmt.insert-id.php) - (mysqli\_stmt\_insert\_id)获取先前INSERT操作生成的ID
*   [mysqli\_stmt::more\_results](http://php.p2hp.com/manual/zh/mysqli-stmt.more-results.php) - (mysqli\_stmt\_more\_results) 检查多个查询是否有更多查询结果
*   [mysqli\_stmt::next\_result](http://php.p2hp.com/manual/zh/mysqli-stmt.next-result.php) - (mysqli\_stmt\_next\_result)从多个查询中读取下一个结果
*   [mysqli\_stmt::$num\_rows](http://php.p2hp.com/manual/zh/mysqli-stmt.num-rows.php) - (mysqli\_stmt\_num\_rows)返回语句结果集中的行数
*   [mysqli\_stmt::$param\_count](http://php.p2hp.com/manual/zh/mysqli-stmt.param-count.php) - (mysqli\_stmt\_param\_count)返回给定语句的参数个数
*   [mysqli\_stmt::prepare](http://php.p2hp.com/manual/zh/mysqli-stmt.prepare.php) - (mysqli\_stmt\_prepare)准备一条SQL语句以便执行
*   [mysqli\_stmt::reset](http://php.p2hp.com/manual/zh/mysqli-stmt.reset.php) - (mysqli\_stmt\_reset)重置预准备语句
*   [mysqli\_stmt::result\_metadata](http://php.p2hp.com/manual/zh/mysqli-stmt.result-metadata.php) - (mysqli\_stmt\_result\_metadata)从[预](http://php.p2hp.com/manual/zh/mysqli-stmt.result-metadata.php)准备语句返回结果集元数据
*   [mysqli\_stmt::send\_long\_data](http://php.p2hp.com/manual/zh/mysqli-stmt.send-long-data.php) - (mysqli\_stmt\_send\_long\_data)以块为单位发送数据
*   [mysqli\_stmt::$sqlstate](http://php.p2hp.com/manual/zh/mysqli-stmt.sqlstate.php) - (mysqli\_stmt\_sqlstate)从前一个语句操作返回SQLSTATE错误
*   [mysqli\_stmt::store\_result](http://php.p2hp.com/manual/zh/mysqli-stmt.store-result.php) - (mysqli\_stmt\_store\_result)从[预](http://php.p2hp.com/manual/zh/mysqli-stmt.store-result.php)准备语句中传输结果集

mysqli\_result - mysqli\_result类  

*   [mysqli\_result::$current\_field](http://php.p2hp.com/manual/zh/mysqli-result.current-field.php) - (mysqli\_field\_tell)获取结果指针的当前字段偏移量
*   [mysqli\_result::data\_seek](http://php.p2hp.com/manual/zh/mysqli-result.data-seek.php) - (mysqli\_data\_seek)将结果指针调整为结果中的任意行
*   [mysqli\_result::fetch\_all](http://php.p2hp.com/manual/zh/mysqli-result.fetch-all.php) - (mysqli\_fetch\_all)将所有结果行[提取](http://php.p2hp.com/manual/zh/mysqli-result.fetch-all.php)为关联数组，数字数组或两者
*   [mysqli\_result::fetch\_array](http://php.p2hp.com/manual/zh/mysqli-result.fetch-array.php) - (mysqli\_fetch\_array)将结果行提取为关联行，数字数组或两者
*   [mysqli\_result::fetch\_assoc](http://php.p2hp.com/manual/zh/mysqli-result.fetch-assoc.php) - (mysqli\_fetch\_assoc)将结果行作为关联数组获取
*   [mysqli\_result::fetch\_field\_direct](http://php.p2hp.com/manual/zh/mysqli-result.fetch-field-direct.php) - (mysqli\_fetch\_field\_direct)获取单个字段的元数据
*   [mysqli\_result::fetch\_field](http://php.p2hp.com/manual/zh/mysqli-result.fetch-field.php) - (mysqli\_fetch\_field)返回结果集中的下一个字段
*   [mysqli\_result::fetch\_fields](http://php.p2hp.com/manual/zh/mysqli-result.fetch-fields.php) - (mysqli\_fetch\_fields)返回表示结果集中字段的对象数组
*   [mysqli\_result::fetch\_object](http://php.p2hp.com/manual/zh/mysqli-result.fetch-object.php) - (mysqli\_fetch\_object)将结果集的当前行作为对象返回
*   [mysqli\_result::fetch\_row](http://php.p2hp.com/manual/zh/mysqli-result.fetch-row.php) - (mysqli\_fetch\_row)将结果行作为枚举数组
*   [mysqli\_result::$field\_count](http://php.p2hp.com/manual/zh/mysqli-result.field-count.php) - (mysqli\_num\_fields)获取结果中的字段数
*   [mysqli\_result::field\_seek](http://php.p2hp.com/manual/zh/mysqli-result.field-seek.php) - (mysqli\_field\_seek)将结果指针设置为指定的字段偏移量
*   [mysqli\_result::free](http://php.p2hp.com/manual/zh/mysqli-result.free.php) - (mysqli\_free\_result)释放与结果相关的内存
*   [mysqli\_result::$lengths](http://php.p2hp.com/manual/zh/mysqli-result.lengths.php) - (mysqli\_fetch\_lengths)返回结果集中当前行的列长度
*   [mysqli\_result::$num\_rows](http://php.p2hp.com/manual/zh/mysqli-result.num-rows.php) - (mysqli\_num\_rows)获取结果中的行数

*   [mysqli\_driver](http://php.p2hp.com/manual/zh/class.mysqli-driver.php) — The mysqli\_driver class
    *   [mysqli\_driver::embedded\_server\_end](http://php.p2hp.com/manual/zh/mysqli-driver.embedded-server-end.php) — Stop embedded server
    *   [mysqli\_driver::embedded\_server\_start](http://php.p2hp.com/manual/zh/mysqli-driver.embedded-server-start.php) — Initialize and start embedded server
    *   [mysqli\_driver::$report\_mode](http://php.p2hp.com/manual/zh/mysqli-driver.report-mode.php) — Enables or disables internal report functions
*   [mysqli\_warning](http://php.p2hp.com/manual/zh/class.mysqli-warning.php) — The mysqli\_warning class
    *   [mysqli\_warning::next](http://php.p2hp.com/manual/zh/mysqli-warning.next.php) — Fetch next warning
*   [mysqli\_sql\_exception](http://php.p2hp.com/manual/zh/class.mysqli-sql-exception.php) — The mysqli\_sql\_exception class
别名和不推荐使用的Mysqli函数  

*   [mysqli\_connect](http://php.p2hp.com/manual/zh/function.mysqli-connect.php) — mysqli::\_\_construct的别名
*   [mysqli\_escape\_string](http://php.p2hp.com/manual/zh/function.mysqli-escape-string.php) — mysqli\_real\_escape\_string的别名
*   [mysqli\_execute](http://php.p2hp.com/manual/zh/function.mysqli-execute.php) — mysqli\_stmt\_execute的别名
*   [mysqli\_get\_client\_stats](http://php.p2hp.com/manual/zh/function.mysqli-get-client-stats.php) — Returns client per-process statistics
*   [mysqli\_get\_links\_stats](http://php.p2hp.com/manual/zh/function.mysqli-get-links-stats.php) — Return information about open and cached links
*   [mysqli\_report](http://php.p2hp.com/manual/zh/function.mysqli-report.php) — mysqli\_driver->report\_mode的别名
*   [mysqli::set\_opt](http://php.p2hp.com/manual/zh/function.mysqli-set-opt.php) — mysqli\_options的别名

  

文件信息Fileinfo
------------

  

*   [finfo\_buffer](http://php.p2hp.com/manual/zh/function.finfo-buffer.php) - 返回有关字符串缓冲区的信息
*   [finfo\_close](http://php.p2hp.com/manual/zh/function.finfo-close.php) - 关闭fileinfo资源
*   [finfo\_file](http://php.p2hp.com/manual/zh/function.finfo-file.php) - 返回有关文件的信息
*   [finfo\_open](http://php.p2hp.com/manual/zh/function.finfo-open.php) - 创建新的fileinfo资源
*   [finfo\_set\_flags](http://php.p2hp.com/manual/zh/function.finfo-set-flags.php) - 设置libmagic配置选项
*   [mime\_content\_type](http://php.p2hp.com/manual/zh/function.mime-content-type.php) - 检测文件的MIME内容类型

*   [finfo](http://php.p2hp.com/manual/zh/class.finfo.php) — finfo 类
    *   [finfo::buffer](http://php.p2hp.com/manual/zh/finfo.buffer.php) — 别名 finfo\_buffer()
    *   [finfo::\_\_construct](http://php.p2hp.com/manual/zh/finfo.construct.php) — 别名 finfo\_open
    *   [finfo::file](http://php.p2hp.com/manual/zh/finfo.file.php) — 别名 finfo\_file()
    *   [finfo::set\_flags](http://php.p2hp.com/manual/zh/finfo.set-flags.php) — 别名 finfo\_set\_flags()


字符集转换iconv
----------

  

*   [iconv\_get\_encoding](http://php.p2hp.com/manual/zh/function.iconv-get-encoding.php) - 检索iconv扩展的内部配置变量
*   [iconv\_mime\_decode\_headers](http://php.p2hp.com/manual/zh/function.iconv-mime-decode-headers.php) - 一次解码多个MIME标头字段
*   [iconv\_mime\_decode](http://php.p2hp.com/manual/zh/function.iconv-mime-decode.php) - 解码MIME标头字段
*   [iconv\_mime\_encode](http://php.p2hp.com/manual/zh/function.iconv-mime-encode.php) - 编写MIME标头字段
*   [iconv\_set\_encoding](http://php.p2hp.com/manual/zh/function.iconv-set-encoding.php) - 设置字符编码转换的当前设置
*   [iconv\_strlen](http://php.p2hp.com/manual/zh/function.iconv-strlen.php) - 返回字符串的字符数
*   [iconv\_strpos](http://php.p2hp.com/manual/zh/function.iconv-strpos.php) - 查找大海捞针中第一次出现针的位置
*   [iconv\_strrpos](http://php.p2hp.com/manual/zh/function.iconv-strrpos.php) - 查找大海捞针中最后一次出现的针
*   [iconv\_substr](http://php.p2hp.com/manual/zh/function.iconv-substr.php) - 剪切掉一部分字符串
*   [iconv](http://php.p2hp.com/manual/zh/function.iconv.php) - 将字符串转换为请求的字符编码
*   [ob\_iconv\_handler](http://php.p2hp.com/manual/zh/function.ob-iconv-handler.php) - 将字符编码转换为输出缓冲区处理程序

  

图像处理GD
------

  

*   [gd\_info](http://php.p2hp.com/manual/zh/function.gd-info.php) - 检索有关当前安装的GD库的信息
*   [getimagesize](http://php.p2hp.com/manual/zh/function.getimagesize.php) - 获取图像的大小
*   [getimagesizefromstring](http://php.p2hp.com/manual/zh/function.getimagesizefromstring.php) - 从字符串中获取图像的大小
*   [image\_type\_to\_extension](http://php.p2hp.com/manual/zh/function.image-type-to-extension.php) - 获取图像类型的文件扩展名
*   [image\_type\_to\_mime\_type](http://php.p2hp.com/manual/zh/function.image-type-to-mime-type.php) - 获取getimagesize，exif\_read\_data，exif\_t​​humbnail，exif\_imagetype返回的图像类型的Mime-Type
*   [image2wbmp](http://php.p2hp.com/manual/zh/function.image2wbmp.php) - 将图像输出到浏览器或文件
*   [imageaffine](http://php.p2hp.com/manual/zh/function.imageaffine.php) - 使用可选的剪切区域返回包含仿射变换的src图像的图像
*   [imageaffinematrixconcat](http://php.p2hp.com/manual/zh/function.imageaffinematrixconcat.php) - 连接两个仿射变换矩阵
*   [imageaffinematrixget](http://php.p2hp.com/manual/zh/function.imageaffinematrixget.php) - 获取仿射变换矩阵
*   [imagealphablending](http://php.p2hp.com/manual/zh/function.imagealphablending.php) - 设置图像的混合模式
*   [imageantialias](http://php.p2hp.com/manual/zh/function.imageantialias.php) - 是否应使用抗锯齿功能
*   [imagearc](http://php.p2hp.com/manual/zh/function.imagearc.php) - 绘制弧形
*   [imagebmp](http://php.p2hp.com/manual/zh/function.imagebmp.php) - 将BMP图像输出到浏览器或文件
*   [imagechar](http://php.p2hp.com/manual/zh/function.imagechar.php) - 水平绘制一个字符
*   [imagecharup](http://php.p2hp.com/manual/zh/function.imagecharup.php) - 垂直绘制一个字符
*   [imagecolorallocate](http://php.p2hp.com/manual/zh/function.imagecolorallocate.php) - 为图像分配颜色
*   [imagecolorallocatealpha](http://php.p2hp.com/manual/zh/function.imagecolorallocatealpha.php) - 为图像分配颜色
*   [imagecolorat](http://php.p2hp.com/manual/zh/function.imagecolorat.php) - 获取像素颜色的索引
*   [imagecolorclosest](http://php.p2hp.com/manual/zh/function.imagecolorclosest.php) - 获取与指定颜色最接近的颜色的索引
*   [imagecolorclosestalpha](http://php.p2hp.com/manual/zh/function.imagecolorclosestalpha.php) - 获取与指定颜色+ alpha最接近的颜色的索引
*   [imagecolorclosesthwb](http://php.p2hp.com/manual/zh/function.imagecolorclosesthwb.php) - 获取具有色调，白色和黑度的颜色的索引
*   [imagecolordeallocate](http://php.p2hp.com/manual/zh/function.imagecolordeallocate.php) - 为图像取消分配颜色
*   [imagecolorexact](http://php.p2hp.com/manual/zh/function.imagecolorexact.php) - 获取指定颜色的索引
*   [imagecolorexactalpha](http://php.p2hp.com/manual/zh/function.imagecolorexactalpha.php) - 获取指定颜色+ alpha的索引
*   [imagecolormatch](http://php.p2hp.com/manual/zh/function.imagecolormatch.php) - 使图像调色板版本的颜色更接近真实颜色版本
*   [imagecolorresolve](http://php.p2hp.com/manual/zh/function.imagecolorresolve.php) - 获取指定颜色的索引或其最接近的替代颜色
*   [imagecolorresolvealpha](http://php.p2hp.com/manual/zh/function.imagecolorresolvealpha.php) - 获取指定颜色的索引+ alpha或其最接近的替代选项
*   [imagecolorset](http://php.p2hp.com/manual/zh/function.imagecolorset.php) - 设置指定调色板索引的颜色
*   [imagecolorsforindex](http://php.p2hp.com/manual/zh/function.imagecolorsforindex.php) - 获取索引的颜色
*   [imagecolorstotal](http://php.p2hp.com/manual/zh/function.imagecolorstotal.php) - 找出图像调色板中的颜色数
*   [imagecolortransparent](http://php.p2hp.com/manual/zh/function.imagecolortransparent.php) - 将颜色定义为透明
*   [imageconvolution](http://php.p2hp.com/manual/zh/function.imageconvolution.php) - 使用系数和偏移量应用3x3卷积矩阵
*   [imagecopy](http://php.p2hp.com/manual/zh/function.imagecopy.php) - 复制图像的一部分
*   [imagecopymerge](http://php.p2hp.com/manual/zh/function.imagecopymerge.php) - 复制并合并图像的一部分
*   [imagecopymergegray](http://php.p2hp.com/manual/zh/function.imagecopymergegray.php) - 使用灰度复制和合并图像的一部分
*   [imagecopyresampled](http://php.p2hp.com/manual/zh/function.imagecopyresampled.php) - 使用重新采样复制和调整图像的一部分
*   [imagecopyresized](http://php.p2hp.com/manual/zh/function.imagecopyresized.php) - 复制和调整图像的一部分
*   [imagecreate](http://php.p2hp.com/manual/zh/function.imagecreate.php) - 创建一个新的基于调色板的图像
*   [imagecreatefrombmp](http://php.p2hp.com/manual/zh/function.imagecreatefrombmp.php) - 从文件或URL创建新图像
*   [imagecreatefromgd2](http://php.p2hp.com/manual/zh/function.imagecreatefromgd2.php) - 从GD2文件或URL创建新图像
*   [imagecreatefromgd2part](http://php.p2hp.com/manual/zh/function.imagecreatefromgd2part.php) - 从GD2文件或URL的给定部分创建新图像
*   [imagecreatefromgd](http://php.p2hp.com/manual/zh/function.imagecreatefromgd.php) - 从GD文件或URL创建新图像
*   [imagecreatefromgif](http://php.p2hp.com/manual/zh/function.imagecreatefromgif.php) - 从文件或URL创建新图像
*   [imagecreatefromjpeg](http://php.p2hp.com/manual/zh/function.imagecreatefromjpeg.php) - 从文件或URL创建新图像
*   [imagecreatefrompng](http://php.p2hp.com/manual/zh/function.imagecreatefrompng.php) - 从文件或URL创建新图像
*   [imagecreatefromstring](http://php.p2hp.com/manual/zh/function.imagecreatefromstring.php) - 从字符串中的图像流创建新图像
*   [imagecreatefromwbmp](http://php.p2hp.com/manual/zh/function.imagecreatefromwbmp.php) - 从文件或URL创建新图像
*   [imagecreatefromwebp](http://php.p2hp.com/manual/zh/function.imagecreatefromwebp.php) - 从文件或URL创建新图像
*   [imagecreatefromxbm](http://php.p2hp.com/manual/zh/function.imagecreatefromxbm.php) - 从文件或URL创建新图像
*   [imagecreatefromxpm](http://php.p2hp.com/manual/zh/function.imagecreatefromxpm.php) - 从文件或URL创建新图像
*   [imagecreatetruecolor](http://php.p2hp.com/manual/zh/function.imagecreatetruecolor.php) - 创建一个新的真彩色图像
*   [imagecrop](http://php.p2hp.com/manual/zh/function.imagecrop.php) - 将图像裁剪到给定的矩形
*   [imagecropauto](http://php.p2hp.com/manual/zh/function.imagecropauto.php) - 使用其中一种可用模式自动裁剪图像
*   [imagedashedline](http://php.p2hp.com/manual/zh/function.imagedashedline.php) - 画一条虚线
*   [imagedestroy](http://php.p2hp.com/manual/zh/function.imagedestroy.php) - 销毁图像
*   [imageellipse](http://php.p2hp.com/manual/zh/function.imageellipse.php) - 绘制一个椭圆
*   [imagefill](http://php.p2hp.com/manual/zh/function.imagefill.php) - 洪水填充
*   [imagefilledarc](http://php.p2hp.com/manual/zh/function.imagefilledarc.php) - 绘制部分圆弧并填充它
*   [imagefilledellipse](http://php.p2hp.com/manual/zh/function.imagefilledellipse.php) - 绘制填充的椭圆
*   [imagefilledpolygon](http://php.p2hp.com/manual/zh/function.imagefilledpolygon.php) - 绘制填充多边形
*   [imagefilledrectangle](http://php.p2hp.com/manual/zh/function.imagefilledrectangle.php) - 绘制一个填充的矩形
*   [imagefilltoborder](http://php.p2hp.com/manual/zh/function.imagefilltoborder.php) - 洪水填充到特定颜色
*   [imagefilter](http://php.p2hp.com/manual/zh/function.imagefilter.php) - 对图像应用滤镜
*   [imageflip](http://php.p2hp.com/manual/zh/function.imageflip.php) - 使用给定模式翻转图像
*   [imagefontheight](http://php.p2hp.com/manual/zh/function.imagefontheight.php) - 获取字体高度
*   [imagefontwidth](http://php.p2hp.com/manual/zh/function.imagefontwidth.php) - 获取字体宽度
*   [imageftbbox](http://php.p2hp.com/manual/zh/function.imageftbbox.php) - 通过freetype2使用字体给出文本的边界框
*   [imagefttext](http://php.p2hp.com/manual/zh/function.imagefttext.php) - 使用FreeType 2使用字体将文本写入图像
*   [imagegammacorrect](http://php.p2hp.com/manual/zh/function.imagegammacorrect.php) - 对GD图像应用伽马校正
*   [imagegd2](http://php.p2hp.com/manual/zh/function.imagegd2.php) - 将GD2图像输出到浏览器或文件
*   [imagegd](http://php.p2hp.com/manual/zh/function.imagegd.php) - 将GD图像输出到浏览器或文件
*   [imagegetclip](http://php.p2hp.com/manual/zh/function.imagegetclip.php) - 获取剪切矩形
*   [imagegetinterpolation](http://php.p2hp.com/manual/zh/function.imagegetinterpolation.php) — Get the interpolation method
*   [imagegif](http://php.p2hp.com/manual/zh/function.imagegif.php) - 将图像输出到浏览器或文件
*   [imagegrabscreen](http://php.p2hp.com/manual/zh/function.imagegrabscreen.php) - 捕获整个屏幕
*   [imagegrabwindow](http://php.p2hp.com/manual/zh/function.imagegrabwindow.php) - 捕获一个窗口
*   [imageinterlace](http://php.p2hp.com/manual/zh/function.imageinterlace.php) - 启用或禁用隔行扫描
*   [imageistruecolor](http://php.p2hp.com/manual/zh/function.imageistruecolor.php) - 查找图像是否为真彩色图像
*   [imagejpeg](http://php.p2hp.com/manual/zh/function.imagejpeg.php) - 将图像输出到浏览器或文件
*   [imagelayereffect](http://php.p2hp.com/manual/zh/function.imagelayereffect.php) - 设置alpha混合标志以使用分层效果
*   [imageline](http://php.p2hp.com/manual/zh/function.imageline.php) - 画一条线
*   [imageloadfont](http://php.p2hp.com/manual/zh/function.imageloadfont.php) - 加载新字体
*   [imageopenpolygon](http://php.p2hp.com/manual/zh/function.imageopenpolygon.php) - 绘制一个开放的多边形
*   [imagepalettecopy](http://php.p2hp.com/manual/zh/function.imagepalettecopy.php) - 将调色板从一个图像复制到另一个图像
*   [imagepalettetotruecolor](http://php.p2hp.com/manual/zh/function.imagepalettetotruecolor.php) - 将基于调色板的图像转换为真彩色
*   [imagepng](http://php.p2hp.com/manual/zh/function.imagepng.php) - 将PNG图像输出到浏览器或文件
*   [imagepolygon](http://php.p2hp.com/manual/zh/function.imagepolygon.php) - 绘制多边形
*   [imagerectangle](http://php.p2hp.com/manual/zh/function.imagerectangle.php) - 绘制一个矩形
*   [imageresolution](http://php.p2hp.com/manual/zh/function.imageresolution.php) - 获取或设置图像的分辨率
*   [imagerotate](http://php.p2hp.com/manual/zh/function.imagerotate.php) - 以给定角度旋转图像
*   [imagesavealpha](http://php.p2hp.com/manual/zh/function.imagesavealpha.php) - 保存PNG图像时是否保留完整的Alpha通道信息
*   [imagescale](http://php.p2hp.com/manual/zh/function.imagescale.php) - 使用给定的新宽度和高度缩放图像
*   [imagesetbrush](http://php.p2hp.com/manual/zh/function.imagesetbrush.php) - 为画线设置画笔图像
*   [imagesetclip](http://php.p2hp.com/manual/zh/function.imagesetclip.php) - 设置剪切矩形
*   [imagesetinterpolation](http://php.p2hp.com/manual/zh/function.imagesetinterpolation.php) - 设置插值方法
*   [imagesetpixel](http://php.p2hp.com/manual/zh/function.imagesetpixel.php) - 设置单个像素
*   [imagesetstyle](http://php.p2hp.com/manual/zh/function.imagesetstyle.php) - 设置线条绘制的样式
*   [imagesetthickness](http://php.p2hp.com/manual/zh/function.imagesetthickness.php) - 设置线条图的粗细
*   [imagesettile](http://php.p2hp.com/manual/zh/function.imagesettile.php) - 设置要填充的图块图像
*   [imagestring](http://php.p2hp.com/manual/zh/function.imagestring.php) - 水平绘制一个字符串
*   [imagestringup](http://php.p2hp.com/manual/zh/function.imagestringup.php) - 垂直绘制一个字符串
*   [imagesx](http://php.p2hp.com/manual/zh/function.imagesx.php) - 获取图像宽度
*   [imagesy](http://php.p2hp.com/manual/zh/function.imagesy.php) - 获取图像高度
*   [imagetruecolortopalette](http://php.p2hp.com/manual/zh/function.imagetruecolortopalette.php) - 将真彩色图像转换为调色板图像
*   [imagettfbbox](http://php.p2hp.com/manual/zh/function.imagettfbbox.php) - 使用TrueType字体给出文本的边界框
*   [imagettftext](http://php.p2hp.com/manual/zh/function.imagettftext.php) - 使用TrueType字体将文本写入图像
*   [imagetypes](http://php.p2hp.com/manual/zh/function.imagetypes.php) - 返回此PHP版本支持的图像类型
*   [imagewbmp](http://php.p2hp.com/manual/zh/function.imagewbmp.php) - 将图像输出到浏览器或文件
*   [imagewebp](http://php.p2hp.com/manual/zh/function.imagewebp.php) - 将WebP图像输出到浏览器或文件
*   [imagexbm](http://php.p2hp.com/manual/zh/function.imagexbm.php) - 将XBM图像输出到浏览器或文件
*   [iptcembed](http://php.p2hp.com/manual/zh/function.iptcembed.php) - 将二进制IPTC数据嵌入JPEG图像
*   [iptcparse](http://php.p2hp.com/manual/zh/function.iptcparse.php) - 将二进制IPTC块解析为单个标记
*   [jpeg2wbmp](http://php.p2hp.com/manual/zh/function.jpeg2wbmp.php) - 将JPEG图像文件转换为WBMP图像文件
*   [png2wbmp](http://php.p2hp.com/manual/zh/function.png2wbmp.php) - 将PNG图像文件转换为WBMP图像文件

*   [GdImage](http://php.p2hp.com/manual/zh/class.gdimage.php) — The GdImage class


Exif可交换图像信息
-----------

  

*   [exif\_imagetype](http://php.p2hp.com/manual/zh/function.exif-imagetype.php) — 判断一个图像的类型
*   [exif\_read\_data](http://php.p2hp.com/manual/zh/function.exif-read-data.php) — 从 JPEG 或 TIFF文件中读取 EXIF 头信息
*   [exif\_tagname](http://php.p2hp.com/manual/zh/function.exif-tagname.php) — 获取指定索引的头名称
*   [exif\_thumbnail](http://php.p2hp.com/manual/zh/function.exif-thumbnail.php) — 取得嵌入在 TIFF 或 JPEG 图像中的缩略图
*   [read\_exif\_data](http://php.p2hp.com/manual/zh/function.read-exif-data.php) — 别名 exif\_read\_data

  

URLs
----

  

*   [base64\_decode](http://php.p2hp.com/manual/zh/function.base64-decode.php) - 解码用MIME base64编码的数据
*   [base64\_encode](http://php.p2hp.com/manual/zh/function.base64-encode.php) - 使用MIME base64编码数据
*   [get\_headers](http://php.p2hp.com/manual/zh/function.get-headers.php) - 获取服务器发送的所有标头以响应HTTP请求
*   [get\_meta\_tags](http://php.p2hp.com/manual/zh/function.get-meta-tags.php) - 从文件中提取所有元标记内容属性并返回一个数组
*   [http\_build\_query](http://php.p2hp.com/manual/zh/function.http-build-query.php) - 生成URL编码的查询字符串
*   [parse\_url](http://php.p2hp.com/manual/zh/function.parse-url.php) - 解析URL并返回其组件
*   [rawurldecode](http://php.p2hp.com/manual/zh/function.rawurldecode.php) - 解码URL编码的字符串
*   [rawurlencode](http://php.p2hp.com/manual/zh/function.rawurlencode.php) - 根据RFC 3986进行URL编码
*   [urldecode](http://php.p2hp.com/manual/zh/function.urldecode.php) - 解码URL编码的字符串
*   [urlencode](http://php.p2hp.com/manual/zh/function.urlencode.php) - URL编码字符串

  

套接字Sockets
----------

  

*   [socket\_accept](http://php.p2hp.com/manual/zh/function.socket-accept.php) - 接受套接字上的连接
*   [socket\_addrinfo\_bind](http://php.p2hp.com/manual/zh/function.socket-addrinfo-bind.php) - 从给定的addrinfo创建并绑定到套接字
*   [socket\_addrinfo\_connect](http://php.p2hp.com/manual/zh/function.socket-addrinfo-connect.php) - 从给定的addrinfo创建并连接到套接字
*   [socket\_addrinfo\_explain](http://php.p2hp.com/manual/zh/function.socket-addrinfo-explain.php) - 获取有关addrinfo的信息
*   [socket\_addrinfo\_lookup](http://php.p2hp.com/manual/zh/function.socket-addrinfo-lookup.php) - 获取有关给定主机名的getaddrinfo内容的数组
*   [socket\_bind](http://php.p2hp.com/manual/zh/function.socket-bind.php) - 将名称绑定到套接字
*   [socket\_clear\_error](http://php.p2hp.com/manual/zh/function.socket-clear-error.php) - 清除套接字上的错误或上一个错误代码
*   [socket\_close](http://php.p2hp.com/manual/zh/function.socket-close.php) - 关闭套接字资源
*   [socket\_cmsg\_space](http://php.p2hp.com/manual/zh/function.socket-cmsg-space.php) - 计算消息缓冲区大小
*   [socket\_connect](http://php.p2hp.com/manual/zh/function.socket-connect.php) - 在套接字上启动连接
*   [socket\_create\_listen](http://php.p2hp.com/manual/zh/function.socket-create-listen.php) - 在端口上打开套接字以接受连接
*   [socket\_create\_pair](http://php.p2hp.com/manual/zh/function.socket-create-pair.php) - 创建一对无法区分的套接字并将它们存储在一个数组中
*   [socket\_create](http://php.p2hp.com/manual/zh/function.socket-create.php) - 创建套接字(通信端点)
*   [socket\_export\_stream](http://php.p2hp.com/manual/zh/function.socket-export-stream.php) - 将套接字扩展资源导出到封装套接字的流中
*   [socket\_get\_option](http://php.p2hp.com/manual/zh/function.socket-get-option.php) - 获取套接字的套接字选项
*   [socket\_getopt](http://php.p2hp.com/manual/zh/function.socket-getopt.php) - socket\_get\_option的别名
*   [socket\_getpeername](http://php.p2hp.com/manual/zh/function.socket-getpeername.php) - 查询给定套接字的远程端，它可能导致主机/端口或Unix文件系统路径，具体取决于其类型
*   [socket\_getsockname](http://php.p2hp.com/manual/zh/function.socket-getsockname.php) - 查询给定套接字的本地端，该端口可能导致主机/端口或Unix文件系统路径，具体取决于其类型
*   [socket\_import\_stream](http://php.p2hp.com/manual/zh/function.socket-import-stream.php) - 导入流
*   [socket\_last\_error](http://php.p2hp.com/manual/zh/function.socket-last-error.php) - 返回套接字上的最后一个错误
*   [socket\_listen](http://php.p2hp.com/manual/zh/function.socket-listen.php) - 侦听套接字上的连接
*   [socket\_read](http://php.p2hp.com/manual/zh/function.socket-read.php) - 从套接字读取最大长度字节
*   [socket\_recv](http://php.p2hp.com/manual/zh/function.socket-recv.php) - 从连接的套接字接收数据
*   [socket\_recvfrom](http://php.p2hp.com/manual/zh/function.socket-recvfrom.php) - 从套接字接收数据，无论它是否是面向连接的
*   [socket\_recvmsg](http://php.p2hp.com/manual/zh/function.socket-recvmsg.php) - 阅读邮件
*   [socket\_select](http://php.p2hp.com/manual/zh/function.socket-select.php) - 在指定的超时套接字数组上运行select()系统调用
*   [socket\_send](http://php.p2hp.com/manual/zh/function.socket-send.php) - 将数据发送到连接的套接字
*   [socket\_sendmsg](http://php.p2hp.com/manual/zh/function.socket-sendmsg.php) - 发送消息
*   [socket\_sendto](http://php.p2hp.com/manual/zh/function.socket-sendto.php) - 向套接字发送消息，无论它是否已连接
*   [socket\_set\_block](http://php.p2hp.com/manual/zh/function.socket-set-block.php) - 在套接字资源上设置阻塞模式
*   [socket\_set\_nonblock](http://php.p2hp.com/manual/zh/function.socket-set-nonblock.php) - 为文件描述符fd设置非阻塞模式
*   [socket\_set\_option](http://php.p2hp.com/manual/zh/function.socket-set-option.php) - 设置套接字的套接字选项
*   [socket\_setopt](http://php.p2hp.com/manual/zh/function.socket-setopt.php) - socket\_set\_option的别名
*   [socket\_shutdown](http://php.p2hp.com/manual/zh/function.socket-shutdown.php) - 关闭套接字以接收，发送或两者兼而有之
*   [socket\_strerror](http://php.p2hp.com/manual/zh/function.socket-strerror.php) - 返回描述套接字错误的字符串
*   [socket\_write](http://php.p2hp.com/manual/zh/function.socket-write.php) - 写入套接字
*   [socket\_wsaprotocol\_info\_export](http://php.p2hp.com/manual/zh/function.socket-wsaprotocol-info-export.php) - 导出WSAPROTOCOL\_INFO结构
*   [socket\_wsaprotocol\_info\_import](http://php.p2hp.com/manual/zh/function.socket-wsaprotocol-info-import.php) - 从另一个进程导入套接字
*   [socket\_wsaprotocol\_info\_release](http://php.p2hp.com/manual/zh/function.socket-wsaprotocol-info-release.php) - 释放导出的WSAPROTOCOL\_INFO结构

*   [Socket](http://php.p2hp.com/manual/zh/class.socket.php) — The Socket class
*   [AddressInfo](http://php.p2hp.com/manual/zh/class.addressinfo.php) — The AddressInfo class


XML解析器
------

  

*   [utf8\_decode](http://php.p2hp.com/manual/zh/function.utf8-decode.php) - 将使用UTF-8编码的ISO-8859-1字符转换为单字节ISO-8859-1
*   [utf8\_encode](http://php.p2hp.com/manual/zh/function.utf8-encode.php) - 将ISO-8859-1字符串编码为UTF-8
*   [xml\_error\_string](http://php.p2hp.com/manual/zh/function.xml-error-string.php) - 获取XML解析器错误字符串
*   [xml\_get\_current\_byte\_index](http://php.p2hp.com/manual/zh/function.xml-get-current-byte-index.php) - 获取XML解析器的当前字节索引
*   [xml\_get\_current\_column\_number](http://php.p2hp.com/manual/zh/function.xml-get-current-column-number.php) - 获取XML解析器的当前列号
*   [xml\_get\_current\_line\_number](http://php.p2hp.com/manual/zh/function.xml-get-current-line-number.php) - 获取XML解析器的当前行号
*   [xml\_get\_error\_code](http://php.p2hp.com/manual/zh/function.xml-get-error-code.php) - 获取XML解析器错误代码
*   [xml\_parse\_into\_struct](http://php.p2hp.com/manual/zh/function.xml-parse-into-struct.php) - 将XML数据解析为数组结构
*   [xml\_parse](http://php.p2hp.com/manual/zh/function.xml-parse.php) - 开始解析XML文档
*   [xml\_parser\_create\_ns](http://php.p2hp.com/manual/zh/function.xml-parser-create-ns.php) - 创建具有名称空间支持的XML解析器
*   [xml\_parser\_create](http://php.p2hp.com/manual/zh/function.xml-parser-create.php) - 创建XML解析器
*   [xml\_parser\_free](http://php.p2hp.com/manual/zh/function.xml-parser-free.php) - 免费的XML解析器
*   [xml\_parser\_get\_option](http://php.p2hp.com/manual/zh/function.xml-parser-get-option.php) - 从XML解析器中获取选项
*   [xml\_parser\_set\_option](http://php.p2hp.com/manual/zh/function.xml-parser-set-option.php) - 在XML解析器中设置选项
*   [xml\_set\_character\_data\_handler](http://php.p2hp.com/manual/zh/function.xml-set-character-data-handler.php) - 设置字符数据处理程序
*   [xml\_set\_default\_handler](http://php.p2hp.com/manual/zh/function.xml-set-default-handler.php) - 设置默认处理程序
*   [xml\_set\_element\_handler](http://php.p2hp.com/manual/zh/function.xml-set-element-handler.php) - 设置开始和结束元素处理程序
*   [xml\_set\_end\_namespace\_decl\_handler](http://php.p2hp.com/manual/zh/function.xml-set-end-namespace-decl-handler.php) - 设置结束名称空间声明处理程序
*   [xml\_set\_external\_entity\_ref\_handler](http://php.p2hp.com/manual/zh/function.xml-set-external-entity-ref-handler.php) - 设置外部实体引用处理程序
*   [xml\_set\_notation\_decl\_handler](http://php.p2hp.com/manual/zh/function.xml-set-notation-decl-handler.php) - 设置表示法声明处理程序
*   [xml\_set\_object](http://php.p2hp.com/manual/zh/function.xml-set-object.php) - 在对象中使用XML Parser
*   [xml\_set\_processing\_instruction\_handler](http://php.p2hp.com/manual/zh/function.xml-set-processing-instruction-handler.php) - 设置处理指令(PI)处理程序
*   [xml\_set\_start\_namespace\_decl\_handler](http://php.p2hp.com/manual/zh/function.xml-set-start-namespace-decl-handler.php) - 设置启动命名空间声明处理程序
*   [xml\_set\_unparsed\_entity\_decl\_handler](http://php.p2hp.com/manual/zh/function.xml-set-unparsed-entity-decl-handler.php) - 设置未解析的实体声明处理程序

*   [XmlParser](http://php.p2hp.com/manual/zh/class.xmlparser.php) — The XmlParser class


OPcache
-------

  

*   [opcache\_compile\_file](http://php.p2hp.com/manual/zh/function.opcache-compile-file.php) — 编译和缓存 PHP 脚本而不执行它
*   [opcache\_get\_configuration](http://php.p2hp.com/manual/zh/function.opcache-get-configuration.php) — 获取有关缓存的配置信息
*   [opcache\_get\_status](http://php.p2hp.com/manual/zh/function.opcache-get-status.php) — 获取有关缓存的状态信息
*   [opcache\_invalidate](http://php.p2hp.com/manual/zh/function.opcache-invalidate.php) — 使缓存的脚本无效
*   [opcache\_is\_script\_cached](http://php.p2hp.com/manual/zh/function.opcache-is-script-cached.php) — 指示脚本是否缓存在 OPCache 中
*   [opcache\_reset](http://php.p2hp.com/manual/zh/function.opcache-reset.php) — 重置操作码缓存的内容

  

APC用户缓存
-------

  

*   [apcu\_add](http://php.p2hp.com/manual/zh/function.apcu-add.php) - 在数据存储中缓存新变量
*   [apcu\_cache\_info](http://php.p2hp.com/manual/zh/function.apcu-cache-info.php) - 从APCu的数据存储中检索缓存信息
*   [apcu\_cas](http://php.p2hp.com/manual/zh/function.apcu-cas.php) - 使用新值更新旧值
*   [apcu\_clear\_cache](http://php.p2hp.com/manual/zh/function.apcu-clear-cache.php) - 清除APCu缓存
*   [apcu\_dec](http://php.p2hp.com/manual/zh/function.apcu-dec.php) - 减少存储的号码
*   [apcu\_delete](http://php.p2hp.com/manual/zh/function.apcu-delete.php) - 从缓存中删除存储的变量
*   [apcu\_enabled](http://php.p2hp.com/manual/zh/function.apcu-enabled.php) — Whether APCu is usable in the current environment
*   [apcu\_entry](http://php.p2hp.com/manual/zh/function.apcu-entry.php) - 以原子方式获取或生成缓存条目
*   [apcu\_exists](http://php.p2hp.com/manual/zh/function.apcu-exists.php) - 检查条目是否存在
*   [apcu\_fetch](http://php.p2hp.com/manual/zh/function.apcu-fetch.php) - 从缓存中获取存储的变量
*   [apcu\_inc](http://php.p2hp.com/manual/zh/function.apcu-inc.php) - 增加存储的号码
*   [apcu\_key\_info](http://php.p2hp.com/manual/zh/function.apcu-key-info.php) — Get detailed information about the cache key
*   [apcu\_sma\_info](http://php.p2hp.com/manual/zh/function.apcu-sma-info.php) - 检索APCu共享内存分配信息
*   [apcu\_store](http://php.p2hp.com/manual/zh/function.apcu-store.php) - 在数据存储中缓存变量

*   [APCUIterator](http://php.p2hp.com/manual/zh/class.apcuiterator.php) — The APCUIterator class
    *   [APCUIterator::\_\_construct](http://php.p2hp.com/manual/zh/apcuiterator.construct.php) — Constructs an APCUIterator iterator object
    *   [APCUIterator::current](http://php.p2hp.com/manual/zh/apcuiterator.current.php) — Get current item
    *   [APCUIterator::getTotalCount](http://php.p2hp.com/manual/zh/apcuiterator.gettotalcount.php) — Get total count
    *   [APCUIterator::getTotalHits](http://php.p2hp.com/manual/zh/apcuiterator.gettotalhits.php) — Get total cache hits
    *   [APCUIterator::getTotalSize](http://php.p2hp.com/manual/zh/apcuiterator.gettotalsize.php) — Get total cache size
    *   [APCUIterator::key](http://php.p2hp.com/manual/zh/apcuiterator.key.php) — Get iterator key
    *   [APCUIterator::next](http://php.p2hp.com/manual/zh/apcuiterator.next.php) — Move pointer to next item
    *   [APCUIterator::rewind](http://php.p2hp.com/manual/zh/apcuiterator.rewind.php) — Rewinds iterator
    *   [APCUIterator::valid](http://php.p2hp.com/manual/zh/apcuiterator.valid.php) — Checks if current position is valid


外部函数接口
------

  

*   [FFI::addr](http://php.p2hp.com/manual/zh/ffi.addr.php) - 创建一个指向C数据的非托管指针
*   [FFI::alignof](http://php.p2hp.com/manual/zh/ffi.alignof.php) - 获取对齐方式
*   [FFI::arrayType](http://php.p2hp.com/manual/zh/ffi.arraytype.php) - 动态构造新的C数组类型
*   [FFI::cast](http://php.p2hp.com/manual/zh/ffi.cast.php) - 执行C类型转换
*   [FFI::cdef](http://php.p2hp.com/manual/zh/ffi.cdef.php) - 创建一个新的FFI对象
*   [FFI::free](http://php.p2hp.com/manual/zh/ffi.free.php) - 释放非托管数据结构
*   [FFI::isNull](http://php.p2hp.com/manual/zh/ffi.isnull.php) — Checks whether a FFI\\CData is a null pointer
*   [FFI::load](http://php.p2hp.com/manual/zh/ffi.load.php) - 从C头文件加载C声明
*   [FFI::memcmp](http://php.p2hp.com/manual/zh/ffi.memcmp.php) - 比较内存区域
*   [FFI::memcpy](http://php.p2hp.com/manual/zh/ffi.memcpy.php) - 将一个内存区域复制到另一个内存区域
*   [FFI::memset](http://php.p2hp.com/manual/zh/ffi.memset.php) - 填充内存区域
*   [FFI::new](http://php.p2hp.com/manual/zh/ffi.new.php) - 创建C数据结构
*   [FFI::scope](http://php.p2hp.com/manual/zh/ffi.scope.php) - 使用在预加载期间解析的C声明实例化FFI对象
*   [FFI::sizeof](http://php.p2hp.com/manual/zh/ffi.sizeof.php) - 获取C数据或类型的大小
*   [FFI::string](http://php.p2hp.com/manual/zh/ffi.string.php) - 从内存区域创建PHP字符串
*   [FFI::type](http://php.p2hp.com/manual/zh/ffi.type.php) - 从C声明创建FFI\\CType对象
*   [FFI::typeof](http://php.p2hp.com/manual/zh/ffi.typeof.php) - 获取FFI\\CData的FFI\\CType

*   [FFI\\CData](http://php.p2hp.com/manual/zh/class.ffi-cdata.php) — C Data Handles
*   [FFI\\CType](http://php.p2hp.com/manual/zh/class.ffi-ctype.php) — C Type Handles
*   [FFI\\Exception](http://php.p2hp.com/manual/zh/class.ffi-exception.php) — FFI Exceptions
*   [FFI\\ParserException](http://php.p2hp.com/manual/zh/class.ffi-parserexception.php) — FFI Parser Exceptions


MongoDB
-------


TODO  

Redis
-----


*   [参考https://github.com/phpredis/phpredis](https://github.com/phpredis/phpredis)

　 last modified :2020-12-27 15:42:00  
TODO:FTP,PCNTL,memcache,memcached,ssh2,Sodium


