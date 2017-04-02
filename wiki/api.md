## 首页

```
api:homePageInfo
{
  banner:[
    {
      productId:1,
      imageUrl:'',
    }
  ],
  promotion:{
    title: '' //促销标题
    promotionList: [//促销
    {
      productId:1,
      imageUrl:'',
      name:'',
      activityPrice:50.00,//促销价
      originalPrice:60.00,//原价
    }]
  },
  productList:[
     {
      productId:1,
      imageUrl:'',
      name:'',
      activityPrice:50.00,//促销价
      originalPrice:60.00,//原价
      describe:''//描述
    }
  ],
  homeFooter:[
    {
      name:'首页',
      link:'http://'
    },
    {
      name:'购物车',
      link:'http://'
    },
    {
      name:'我的',
      link:'http://'
    }
  ]
}
```

## 商品详情

```
api:detail?id
{
  productId:1,
  name:'蒙牛牛奶',
  imageUrl:'http://',
  detailedDes:{
    description:'',     //商品介绍 图片
    specParam:'',       //规格参数 图片
    customerServ:''     //售后服务 图片
  }, //商品详细描述
  spec:[],//规格
  newEvaluate:{         //最近一次的评价
    nickname:'',        //昵称
    message:''          //评价
  },
  evaluate:'http://',   //评价链接
}
```
