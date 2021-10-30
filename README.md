```assembly
data segment 
    string db 'Hello,World!$'
data ends
code segment 
assume cs:code,ds:data
start:
    mov ax,data 
    mov ds,ax 
    mov dx,offset string
    mov ah,9
    int 21h
    mov ah,4ch
    int 21h
code ends
end start
```


# Teikumo DESU!!
### Salut.
- Teikumoは:
- proletariat/communist/hax/anime lover/IJN lover. 
- Уг нь би Монголд төрсөн XD
- 在中国内地学习中
- Би өөрийгөө хэн бэ гэдэгт эргэлзэх хэрэгтэй гэж бодож байна.
- Quit HVH now.

<img src="https://github.com/M3351AN/db/raw/main/DSC05356.JPG" width = "800" height = "600" alt="SHIGURE!!" align=center />

[![Github Stats](https://github-readme-stats.vercel.app/api?username=M3351AN&theme=tokyonight&show_icons=true)](https://github.com/M3351AN)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs?username=M3351AN&layout=compact)](https://github.com/M3351AN)



