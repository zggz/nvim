
# 缓冲区列表

- 一个窗口内切换历史文件
> 查看 
- ls
> 状态
- % 表示当前窗口的文件
- `#` 表示轮换文件
- h+ 表示一个隐藏缓冲区，未进行写入的更改
## 切换文件
- 可以通过 control + ^ 
- 触摸板点点点
> 命令
* :bn   bnext 下一个
* :bp   bprev 上一个
* :bf   bfirst 跳转到第一个
* :bl   blast 跳转到最后一个
> 多个文件切换
- :b{number} 可以通过数字切换到指定文件
> 强制切换
- 在切换命令后面添加感叹号（:bn!）
## 删除缓冲区
- :bd{number} 删除指定的缓冲区记录

# 写入文件
- w[rite]   写入当前文件的更改
- e[dit]!   放弃当前文件的修改
- wa[ll]!   写入所有修改 
- qa[all]!  放弃所有修改

# 多窗口
## 拆分窗口
> 垂直拆分
- :vs
> 水平拆分
- :vs
## 关闭窗口
- :clo[se]  关闭当前窗口
- :on[ly]   只保留当前窗口
## 切换窗口
- control + w {j,k,h,l,t,b}

# 新建文件
>  当前窗口新建文件
- :n filename 
>  垂直拆分新建文件
- :vnew filename 

# 编辑文件
>  打开当前文件或新建文件
- :e[dit] filename 

