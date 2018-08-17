# 图片墙 demo
主要运用到浮动与清除浮动

```CSS
.all-card::after{
  content: '';
  display: block;
  clear: both;
}

.all-card .card {
  margin-left: 10px;
  margin-top: 30px;
  list-style: none;
  float: left;
}
```