---
title: "Interpreting principal component values"
image: "https:\/\/i.ytimg.com\/vi\/fpR1sGfnphw\/hqdefault.jpg"
vid_id: "fpR1sGfnphw"
categories: "Education"
tags: ["principal component analysis","PCA","interpreting PCA"]
date: "2022-02-04T07:15:48+03:00"
vid_date: "2018-06-19T01:23:06Z"
duration: "PT13M10S"
viewcount: "2626"
likeCount: "42"
dislikeCount: ""
channel: "Malik McPherson"
---
{% raw %}The dataset is made available through the following link: <a rel="nofollow" target="blank" href="https://drive.google.com/file/d/1GmJWk8vFc6KC-TrrvGceaHW2HE4SZn6e/view?usp=sharing">https://drive.google.com/file/d/1GmJWk8vFc6KC-TrrvGceaHW2HE4SZn6e/view?usp=sharing</a><br /><br />R code used:<br />library(factoextra)<br />library(ggplot2)<br />library(corrplot)<br />diab=read.table(&quot;diab.txt&quot;,header=T)<br />head(diab)<br />dim(diab)<br />diab.pca=prcomp(diab,scale=T)<br />var=get_pca_var(diab.pca)<br />var<br />eig.val=get_eigenvalue(diab.pca)<br />eig.val<br />fviz_eig(diab.pca, addlabels = T, ylim = c(0, 30))<br />fviz_pca_var(diab.pca, col.var = &quot;blue&quot;)<br />fviz_contrib(diab.pca,choice = &quot;var&quot;, axes = 1)<br />fviz_contrib(diab.pca, choice = &quot;var&quot;, axes = 2)<br />fviz_contrib(diab.pca, choice = &quot;var&quot;, axes = 3)<br />fviz_contrib(diab.pca, choice = &quot;var&quot;, axes = 4)<br />corrplot(var$cos2, is.corr=FALSE)<br />X11()<br />corrplot(var$contrib, is.corr=F) <br />diab.pca{% endraw %}
