﻿https://www.mediawiki.org/wiki/Extension:MsUpload 已经更新至9.4版本，需要将萌娘百科当前用的 修改过的9.2版代码与9.4合并。

修改版添加了图片注释自动添加分类（category:pagename）以及额外的作者名和源地址输入框

这里储存的是MsUpload9.4版本，萌娘百科正在使用的版本可以在 https://github.com/moegirlwiki/Moegirlwiki/tree/develop/extensions/MsUpload 找到



http://see.sl088.com/wiki/%E6%89%A9%E5%B1%95:MsUpload ←这里的一些内容可能会(帮助or阻止)你理解这个插件。

############################################################
#Author:
#Martin Schwindl, msupload@ratin.de
#
#Icons: 
#Some icons by Yusuke Kamiyamane. All rights reserved. Licensed under a Creative Commons Attribution 3.0 License.
#http://p.yusukekamiyamane.com
#
#Usage:
#LocalSettings.php:
#
##Start --------------------------------------- MsUpload
##if necessary
##$wgEnableWriteAPI = true; //API
##$wgEnableUploads = true; // Enable uploads
##$wgFileExtensions = array('png','gif','jpg','jpeg','doc','xls','mpp','pdf','ppt','tiff','bmp','docx', 'xlsx', 'pptx','ps','odt','ods','odp','odg');
#
#$wgMSU_ShowAutoKat = true;     #autokategorisierung
#$wgMSU_CheckedAutoKat = true;  #checkbox: checked = true/false
#$wgMSU_debug = false;
#$wgMSU_ImgParams = "400px";
$wgMSU_UseDragDrop = true; 	#show Drag&Drop Area?	
#require_once("$IP/extensions/MsUpload/msupload.php");
##End  --------------------------------------- MsUpload
#
#
############################################################
