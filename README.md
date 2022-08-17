<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Responsive Layout</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 10px;
  text-align: center;
}

div{
  background-color: darkgray;
  height:150px

}

p {
  font-family: Helvetica;
margin-top: 40px;
}

#p1{
  background-color: lightpink;
  float: right;
  margin: auto;
  clear: left;
  height: 30px;
  width: 80px;
  text-align: center;


}

#p2{
  background-color: mediumvioletred;
    color: white;
  float: right;
  margin: auto;
  clear: left;
  height: 30px;
  width: 80px;
    text-align: center;


}

#p3{
  background-color: lightyellow;
  float: right;
  margin: auto;
  clear: left;
  height: 30px;
  width: 80px;
    text-align: center;
    position: relative;

}


/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** desktop view only **********/
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    border: 1px solid green;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** browser window only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid green;
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

  
/********** browser window only **********/
@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
    border: 1px solid green;
  }
  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16.66%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33%;
  }
  .col-sm-5 {
    width: 41.66%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.33%;
  }
  .col-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }
}
  
  
</style>
</head>
<body>
<h1>菜谱</h1>

<div class="row">
  <div class="col-lg-4 col-md-6 col-sm-12">
    <p id=p1>
      
      宫保鸡丁
    </p>

    <p>
      
      宫保鸡丁是四川的传统名菜，传说是清末时由太子少保丁宝桢的家厨创制而成。有时他忙于公务回府晚，家厨摸准了大人的脾气，便在厨房内随手抓些现成的鸡丁、辣子及花生米之类，热锅快炒后送上，甚得丁大人欢心。
    </p>

  </div>

  <div class="col-lg-4 col-md-6 col-sm-12"">
    <p id=p2>
      鱼香肉丝
    </p>

    <p>
Yuxiang shredded pork (simplified Chinese: 鱼香肉丝; traditional Chinese: 魚香肉絲; pinyin: yúxiāng ròusī; sometimes translated as fish-flavored pork slices, or more vaguely as shredded pork with garlic sauce) is a common dish in Sichuan cuisine. 
    </p>
  </div>

  <div class="col-lg-4 col-md-12 col-sm-12"">
    <p id=p3>
      粉蒸肉
    </p>
    <p>
      粉蒸肉（又名面面肉）是广泛流行于中国南方地区的的汉族传统名菜之一、是江西名菜，另在川菜、湘菜、浙菜等中都有这一菜式。以主料带皮五花肉加米粉和其他调味料制作而成。
    </p>
  </div>

</div>

</body>
</html>
