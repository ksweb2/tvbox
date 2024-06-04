{
    "sites": 
    [  
      {"key": "飞飞资源", "name": "🌶飞飞资源", "type": 1, "api": "https://www.feisuzyapi.com/api.php/provide/vod/", "searchable": 1, "quickSearch": 1, "filterable": 0 },
      {"key": "非凡资源", "name": "🍱非凡资源", "type": 1, "api": "https://api.ffzyapi.com/api.php/provide/vod/", "searchable": 1, "quickSearch": 1, "filterable": 0 },
        
       {"key": "push_agent", "name": "推送", "type": 3, "api": "csp_PushAgent", "searchable": 0, "quickSearch": 0, "filterable": 0 }
  ], 
  "lives": [{"group": "redirect", "channels": [{"name": "channels", "urls": ["proxy://do=live&type=txt&ext=aHR0cHM6Ly9hZ2l0LmFpL2NjeS92L3Jhdy9icmFuY2gvbWFzdGVyL3R2L2NuLnR4dA=="] } ] } ], 
  "parses": [
    {"name": "解析聚合", "type": 3, "url": "Demo"},
    {"name": "Json并发", "type": 2, "url": "Parallel"},
    {"name": "Json轮询", "type": 2, "url": "Sequence"},
    {"name": "全站资源", "type": 1, "url": "https://yparse.jn1.cc/index.php?url=", "ext": {"flag": ["youku", "优酷", "mgtv", "芒果", "qq", "腾讯", "qiyi", "爱奇艺", "qq", "奇艺"] } },
    {"name": "江湖解析", "type": 1, "url": "http://103.40.240.46/jh/?url=", "ext": {"flag": ["renrenmi", "qq", "腾讯", "youku", "优酷", "mgtv", "芒果", "xigua", "西瓜"] } },
    {"name": "王牌", "type": 1, "url": "https://za.kuanjv.com/?url=", "ext": {"flag": ["qq", "腾讯", "qiyi", "爱奇艺", "奇艺", "youku", "优酷", "mgtv", "芒果", "搜狐", "sohu", "letv", "乐视", "bilibili", "哔哩哔哩", "哔哩", "xigua", "西瓜"] } },
    {"name": "Wuduzy", "type": 1, "url": "https://aa.xkys.tv/json.php?url=", "ext": {"flag": ["wuduzy"] } },
    {"name": "zui", "type": 0, "url": "https://jx.zui.cm/?url=", "ext": {"flag": ["ltnb"] } },
    {"name": "web1", "type": 0, "url": "https://www.nxflv.com/?url=", "ext": {"flag": ["youku", "优酷", "mgtv", "芒果", "qq", "腾讯", "qiyi", "爱奇艺", "qq", "奇艺", "sohu", "letv"] } },
    {"name": "ltnb04", "type": 0, "url": "https://vip.bljiex.com/?v=", "ext": {"flag": ["ltnb"] } },
    {"name": "ltnb02", "type": 0, "url": "https://jx.zui.cm/?url=", "ext": {"flag": ["ltnb"] } },
    {"name": "parwix1", "type": 0, "url": "https://jx.parwix.com:4433/player/?url=", "ext": {"flag": ["qq", "腾讯", "qiyi", "爱奇艺", "奇艺", "youku", "优酷", "mgtv", "芒果", "letv", "乐视", "pptv", "PPTV", "sohu", "bilibili", "哔哩哔哩", "哔哩"] } },
    {"name": "parwix2", "type": 0, "url": "https://jx.parwix.com:4433/player/analysis.php?v=", "ext": {"flag": ["qq", "腾讯", "qiyi", "爱奇艺", "奇艺", "youku", "优酷", "mgtv", "芒果", "letv", "乐视", "pptv", "PPTV", "sohu", "bilibili", "哔哩哔哩", "哔哩"] } } ], "flags": ["youku", "qq", "iqiyi", "qiyi", "letv", "sohu", "tudou", "pptv", "mgtv", "wasu", "bilibili", "renrenmi", "优酷", "芒果", "腾讯", "爱奇艺", "奇艺", "ltnb", "rx", "CL4K", "xfyun", "wuduzy"],
  "ijk": [
    {"group": "软解码", "options": [
      {"category": 4, "name": "opensles", "value": "0"},
      {"category": 4, "name": "overlay-format", "value": "842225234"},
      {"category": 4, "name": "framedrop", "value": "1"},
      {"category": 4, "name": "soundtouch", "value": "1"},
      {"category": 4, "name": "start-on-prepared", "value": "1"},
      {"category": 1, "name": "http-detect-range-support", "value": "0"},
      {"category": 1, "name": "fflags", "value": "fastseek"},
      {"category": 2, "name": "skip_loop_filter", "value": "48"},
      {"category": 4, "name": "reconnect", "value": "1"},
      {"category": 4, "name": "max-buffer-size", "value": "5242880"},
      {"category": 4, "name": "enable-accurate-seek", "value": "0"},
      {"category": 4, "name": "mediacodec", "value": "0"},
      {"category": 4, "name": "mediacodec-auto-rotate", "value": "0"},
      {"category": 4, "name": "mediacodec-handle-resolution-change", "value": "0"},
      {"category": 4, "name": "mediacodec-hevc", "value": "0"},
      {"category": 1, "name": "dns_cache_timeout", "value": "600000000"} ] },
    {"group": "硬解码", "options": [
      {"category": 4, "name": "opensles", "value": "0"},
      {"category": 4, "name": "overlay-format", "value": "842225234"},
      {"category": 4, "name": "framedrop", "value": "1"},
      {"category": 4, "name": "soundtouch", "value": "1"},
      {"category": 4, "name": "start-on-prepared", "value": "1"},
      {"category": 1, "name": "http-detect-range-support", "value": "0"},
      {"category": 1, "name": "fflags", "value": "fastseek"},
      {"category": 2, "name": "skip_loop_filter", "value": "48"},
      {"category": 4, "name": "reconnect", "value": "1"},
      {"category": 4, "name": "max-buffer-size", "value": "5242880"},
      {"category": 4, "name": "enable-accurate-seek", "value": "0"},
      {"category": 4, "name": "mediacodec", "value": "1"},
      {"category": 4, "name": "mediacodec-auto-rotate", "value": "1"},
      {"category": 4, "name": "mediacodec-handle-resolution-change", "value": "1"},
      {"category": 4, "name": "mediacodec-hevc", "value": "1"},
      {"category": 1, "name": "dns_cache_timeout", "value": "600000000"} 
      ] } 
  ], 
"ads": ["mimg.0c1q0l.cn", "www.googletagmanager.com", "www.google-analytics.com", "mc.usihnbcq.cn", "mg.g1mm3d.cn", "mscs.svaeuzh.cn", "cnzz.hhttm.top", "tp.vinuxhome.com", "cnzz.mmstat.com", "www.baihuillq.com", "s23.cnzz.com", "z3.cnzz.com", "c.cnzz.com", "stj.v1vo.top", "z12.cnzz.com", "img.mosflower.cn", "tips.gamevvip.com", "ehwe.yhdtns.com", "xdn.cqqc3.com", "www.jixunkyy.cn", "sp.chemacid.cn", "hm.baidu.com", "s9.cnzz.com", "z6.cnzz.com", "um.cavuc.com", "mav.mavuz.com", "wofwk.aoidf3.com", "z5.cnzz.com", "xc.hubeijieshikj.cn", "tj.tianwenhu.com", "xg.gars57.cn", "k.jinxiuzhilv.com", "cdn.bootcss.com", "ppl.xunzhuo123.com", "xomk.jiangjunmh.top", "img.xunzhuo123.com", "z1.cnzz.com", "v1.cnzz.com", "s13.cnzz.com", "xg.huataisangao.cn", "z7.cnzz.com", "xg.huataisangao.cn", "z2.cnzz.com", "s96.cnzz.com", "q11.cnzz.com", "thy.dacedsfa.cn", "xg.whsbpw.cn", "s19.cnzz.com", "z8.cnzz.com", "s4.cnzz.com", "f5w.as12df.top", "ae01.alicdn.com", "videocloud.cn-hangzhou.log.aliyuncs.com", "www.92424.cn", "k.wudejia.com", "vivovip.mmszxc.top", "qiu.xixiqiu.com", "cdnjs.hnfenxun.com", "cms.qdwght.com"]}
