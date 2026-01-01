const config = {
  //网页元数据
  metaData:{
    title: 'cnbdg的个人主页🎉',
    description: '欢迎来到cndbg的奇妙世界！',
    keywords: '个人主页,个人网站',
    icon: '/favicon.ico'   //网页图标，支持外链
  },

  avatar: "/img/avatar.jpg", // 头像，请确保你的 img/avatar.jpg 文件存在
  welcometitle: "Hi, I'm cnbdg", // 标题

  // 颜色配置 (保留原作者的默认配置)
  color: {
    themecolor: "#D1FFEC", // 主题颜色，推荐趋于亮白可带有轻微色调，例： #D1FFEC
    welcometitlecolor: "#7BFFC9", // 标题颜色 例： #7BFFC9
    turntablecolor1: "#FFFF00",  // 转盘渐变色一
    turntablecolor2: "#00FFFF"   // 转盘渐变色二
  },
  
  brightness: 85, // 背景亮度 --%
  blur: 5, // 毛玻璃模糊效果

  // 我的标签
  tags : ['开朗','细心','吃货'],

  // 默认背景壁纸 (保留原作者的默认配置)
  background: {
    "pc":{   //pc端
      "type":"pic",   //"pic":静态壁纸;"video":动态壁纸
      "datainfo":{
        "title":"海洋女孩", 
        "preview":"/img/wallpaper/static/海洋女孩/image-pre.webp",
        "url":"/img/wallpaper/static/海洋女孩/image.png",
      },
    },
    "mobile":{   //移动端
      "type":"pic",
      "datainfo":{
        "title":"0001", 
        "preview":"/img/wallpaper/static-mobile/0001/image-pre.webp",
        "url":"/img/wallpaper/static-mobile/0001/image.png"
      }
    }
      
  },

  //极坐标图数据
  polarChart:{
    skills: ['无畏契约', '使命召唤', 'QQ', '微信'],
    skillPoints: [60, 85, 78, 80],
  },

  //社交按钮，图标使用mdi图标（pictogrammers.com），复制图标名称即可
  socialPlatformIcons: [
    {icon:"mdi-github",link:"github.com"}, // 已修复为完整链接
    {icon:"mdi-email",link:"mailto:3606604482@qq.com"},
    {icon:"mdi-qqchat",link:"wpa.qq.com"}, // 已修复为完整链接
    // 微信、YouTube、Facebook 因你填了“无”而移除，如需添加请自行修改
  ],

  //打字机
  typeWriterStrings: [
    "Ciallo～(∠・ω< )⌒★"
  ],

  //音乐播放配置，采用MetingJS Api(github.com) (保留原作者的默认配置)
  musicPlayer:{
    server: 'netease',  //服务提供商 --网易云音乐
    type: 'playlist',   //歌单类型
    id: '2028178887'  //歌单id ---> music.163.com
  },

  //壁纸数据 -----可以将壁纸文件上传到图床获取网络直链。若想调用api，请前往脚本自行修改逻辑 (已修复)
  wallpaper:{
    pic:,
    picMobile:,
    video:[
      {
        "title":"尼尔：机械纪元 团队",
        "preview":"/img/wallpaper/dynamic/尼尔：机械纪元 团队/Nier-Automata-Team-pre.webm",
        "url":"/img/wallpaper/dynamic/尼尔：机械纪元 团队/Nier-Automata-Team.webm"
      },
      {
        "title":"向往航天的女孩",
        "preview":"/img/wallpaper/dynamic/向往航天的女孩/Toy-Aeroplane-pre.webm",
        "url":"/img/wallpaper/dynamic/向往航天的女孩/Toy-Aeroplane.webm"
      },
    ],
    videoMobile:[
      {
        "title":"幻觉镇-gaako_illust",
        "preview":"/img/wallpaper/dynamic-mobile/幻觉镇-gaako_illust/Hallucination_town-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/幻觉镇-gaako_illust/Hallucination_town.mp4"
      },
      {
        "title":"chuva",
        "preview":"/img/wallpaper/dynamic-mobile/chuva/chuva-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/chuva/chuva.mp4"
      },
      {
        "title":"Doodle-小猫女仆降临",
        "preview":"/img/wallpaper/dynamic-mobile/Doodle-小猫女仆降临/d12-pre.mp4",
        "url":"/img/wallpaper/dynamic-mobile/Doodle-小猫女仆降临/d12.mp4"
      },
    ],
  },

  //项目卡片 其中 字段"show"控制初始卡片的text是否展开 (已修复)
  projectcards:,
  
  statement: ["备案号：待更新","Copyright © 2025 cnbdg"],
}
}
