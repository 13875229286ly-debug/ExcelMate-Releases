# Excel Mate

Windows 本地 Excel / CSV 批量整理助手。支持 `.xlsx`、`.xlsm`、真实 `.xls` 和 `.csv` 的合并、字段匹配、缺失字段补齐、去重、筛选、多工作表与 `.xlsx` 导出。

A local Windows spreadsheet assistant for merging Excel/CSV files, aligning columns, filling missing fields, deduplicating, filtering and exporting workbooks.

## 下载 / Downloads

- [最新版安装程序 / Latest Windows installer](https://github.com/13875229286ly-debug/ExcelMate-Releases/releases/latest/download/ExcelMate-Setup.exe)
- [中英文图解操作手册 PDF / Bilingual illustrated user manual](https://github.com/13875229286ly-debug/ExcelMate-Releases/releases/latest/download/ExcelMate-User-Manual.pdf)
- [版本说明与历史 / Release notes and history](https://github.com/13875229286ly-debug/ExcelMate-Releases/releases)

安装包名称始终为 **ExcelMate-Setup.exe**。安装包自带 PDF、离线 HTML 手册、全部配图以及练习文件；安装后点击软件顶部“操作手册 / User guide”即可阅读。

The installer filename stays **ExcelMate-Setup.exe**. It includes PDF and offline HTML guides, all illustrations and practice files. Open **User guide** in the application to read them.

## 当前版本 / Current release

**1.0.7**：自动识别被系统误命名为 `.csv` 的 Excel 工作簿，支持其中的首张、全部或指定工作表；文本 CSV 新增带 BOM 的 UTF-16 / UTF-32 支持，保留 UTF-8 / GB18030。附 26 页、24 章、9 张图解的双语手册；保留中文 / English 界面、7 天试用、离线激活和联网更新。

**1.0.7** detects Excel workbooks misnamed `.csv`, including their first, all or selected worksheets. Text CSV now supports UTF-16 / UTF-32 with BOM alongside UTF-8 / GB18030. It includes a 26-page bilingual guide with 24 chapters and nine illustrations, and retains Chinese and English interfaces, a seven-day trial, offline activation and online updates.

## 开始使用 / Getting started

1. 下载安装器，关闭旧版 Excel Mate，运行安装向导。 Download the installer, close older Excel Mate windows and follow the setup wizard.
2. 打开操作手册，按第 4 章完成练习。 Open User guide and follow the reproducible exercise in Chapter 4.
3. 添加文件，选择工作表和规则，处理并预览，再导出结果。 Add files, choose worksheets and rules, process and preview, then export.
4. 更新前导出要保留的结果。正常升级保留原试用期限、离线激活和语言设置。 Export results you need before updating. Normal upgrades preserve original trial dates, offline activation and language preferences.

表格处理在本机进行，不上传业务文件；联网更新只获取发布文件。旧版没有更新功能或没有配置更新源时，需先手动安装一次当前版本。未使用 Windows Authenticode 付费代码签名，系统可能显示未知发布者提示；请核对下载来源。

Spreadsheet processing stays local. Online updates retrieve release files only. Older versions without a configured update source need one manual installation of the current version. The installer does not have a paid Windows Authenticode certificate, so Windows may show an unknown-publisher notice; verify the download source.

本仓库仅发布客户安装包、操作手册与签名更新文件，不包含商业源码、发码工具、私钥或客户数据。

This repository distributes customer installers, user documentation and signed update metadata. It does not contain commercial source code, seller tools, private keys or customer data.
