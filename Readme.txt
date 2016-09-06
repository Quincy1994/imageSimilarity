test = getImgHash("原图.jpg")
a=getImgHash("1.jpg")#图片地址自行替换
b=getImgHash("2.jpg")
c=getImgHash("3.jpg")
d=getImgHash("4.jpg")

compare=getMH(test,a)
print u'相似度',str(compare)+'%'
compare=getMH(test,b)
print u'相似度',str(compare)+'%'
compare=getMH(test,c)
print u'相似度',str(compare)+'%'
compare=getMH(test,d)
print u'相似度',str(compare)+'%'
