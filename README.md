### 🌎初次见面，请多关照！👋

个人简介：一个写前端的，写过几年后端。
~~~markdown
data segment;
    string db 'Hello,World!$'
data ends
code segment;
assume cs:code,ds:data
start:
    mov ax,data;
    mov ds,ax;
    mov dx,offset string
    mov ah,9
    int 21h
    mov ah,4ch
    int 21h
code ends
end start
~~~
