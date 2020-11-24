## 微擎(WE7)常用函数收集


|函数名称			|参数													|说明											|
|--					|--														|--												|
|createOrderNo		|(无)													| 创建订单编号									|
|url2local			|$src,$domain											|本机url转换为本地路径							|
|isWeixin			|(无)													|是否微信环境									|
|isMobile			|(无)													|是否手机环境									|
|yc_mobile			|$mobile, $index = 3, $starcount = 8					|隐藏手机号中间4位								|
|randomFloat		|$min = 0, $max = 1, $decimals = 2						|返回指定范围内的随机数							|
|mobileUrl			|$do = '', $query = NULL, $full = false					|创建手机端url									|
|deleteDir			|$dir, $delself = false									|删除指定目录下的文件夹和文件					|
|download_remote_pic|$url, $savepath, $ext = 'jpg'							|下载远程图片并返回保存后的完整路径				|
|composeImg			|$src, $bgimg, $savepath								|合成2张图片并返回完整路径						|
|exportexcel		|$title = array(), $data = array(), $filename = 'xx.xls'|导出数据到xls文件								|
|hex2rgb			|$hex													|颜色16进制转RGB								|
|is_weixin			|(无)													|判断是否微信环境，如果不是显示关注公众号二维码	|
|radius_img			|$imgpath = './test.jpg', $radius = 10					|处理圆角图片									|
|register_jssdk_plus|$debug = false											|自定义注册jssdk，增加增加开发标签				|
|debug				|$file, $data											|输出调试文件									|
|dump				|$var,$exit=true										|输出调试信息									|
