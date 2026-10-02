# 网页工作簿

一个下载后双击 HTML 就能使用的本地电子表格。无需安装、登录或联网，仓库只提供空白工作簿。

下载 [index.html](index.html)，用现代浏览器打开。单击选择，双击或直接输入编辑；拖动、Shift 点击和名称框可选择区域。支持复制剪切粘贴、撤销重做、格式设置、合并、行列调整与隐藏、自动填充、冻结首行/首列、排序筛选、查找替换、多个工作表和缩放。菜单与操作提示有轻量动效，并尊重系统的减少动态效果设置。

公式支持加减乘除、比较、百分比、单元格/区域/跨表引用，以及 SUM、AVERAGE、MIN、MAX、COUNT、COUNTA、IF、IFERROR、ROUND、ABS、AND、OR、NOT、COUNTIF、SUMIF、VLOOKUP、INDEX、MATCH、CONCAT、CONCATENATE、LEN、LEFT、RIGHT、UPPER、LOWER、TRIM、TODAY、DATE、YEAR、MONTH、DAY。支持 `$A$1` 绝对引用。

编辑会自动保存在当前浏览器的本地存储中，**不会修改原 HTML 文件**。点击「保存 HTML」生成含数据与格式的独立快照，移动、重命名文件或换设备前请先保存。原有版本的记录可作为 Sheet1 载入。

文件菜单支持 CSV / TSV、JSON 完整备份和基础 `.xlsx` 文件交换。CSV 只保存当前表的显示值；HTML 与 JSON 保存完整工作簿。XLSX 支持基础数据、常用格式、公式、合并、行列尺寸和隐藏状态。导入压缩 XLSX 需要浏览器支持 `DecompressionStream('deflate-raw')`；数据在本机处理。

每张表最多 1000 行、100 列，最多 20 个工作表。此版本实现常用表格操作，不具备完整 Excel 兼容性：宏、图表、透视表、条件格式、数据验证及未列出的函数不受支持；复杂 Excel 文件建议先备份，再导入。字体使用本机字体。
