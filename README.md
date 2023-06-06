skip_render:   #部署时不包含的文件

#单个文件
skip_render: hello.html

#单个文件夹下全部文件
skip_render: test/* 

#单个文件夹下指定类型文件
skip_render: test/*.md  

#单个文件夹下全部文件以及子目录
skip_render: test/**  

#跳过多个目录，或者多个文件
skip_render: ['*.html', demo/**, test/*]