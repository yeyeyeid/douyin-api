# 抖音Api：带同款商品视频列表

## 抖音视频Api、抖音直播Api、抖音评论采集、抖音弹幕采集、抖音爬虫、抖音去水印、抖音视频下载、抖音视频解析
## 抖音直播数据、抖音数据采集、抖音直播监控

#### TiToData：专业的短视频数据采集、处理平台。
> 更多信息请联系微信：ifuxing123
```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博

```


## 抖音Api：带同款商品视频列表

### 请求Api
```http
http://主机地址/douyin/promotion/videos?token=xxx&pid=61088777146700

```

### 

### 请求方式
```http
GET
```

### 

### 参数
| 字段 | 类型 | 说明 |
| --- | --- | --- |
| token | string | 接口授权码 |
| pid	 | int | 商品的promotion_id |


### 

### 返回示例
```json

{
    "code":200,
    "data":{
        "extra":{
            "fatal_item_ids":[
            ],
            "logid":"2020091423131701012912923017205465",
            "now":1600096397000
        },
        "log_pb":{
            "impr_id":"2020091423131701012912923017205465"
        },
        "same_list":[
            Object{...},
            Object{...},
            Object{...},
            Object{...},
            Object{...},
            {
                "anchors":null,
                "author":{
                    "accept_private_policy":false,
                    "account_region":"",
                    "ad_cover_url":null,
                    "apple_account":0,
                    "authority_status":0,
                    "avatar_168x168":{
                        "height":720,
                        "uri":"2f7510004166caf1c896f",
                        "url_list":[
                            "https://p9-dy.byteimg.com/img/2f7510004166caf1c896f~c5_168x168.webp?from=4010531038",
                            "https://p3-dy-ipv6.byteimg.com/img/2f7510004166caf1c896f~c5_168x168.webp?from=4010531038",
                            "https://p29-dy.byteimg.com/img/2f7510004166caf1c896f~c5_168x168.webp?from=4010531038"
                        ],
                        "width":720
                    },
                    "avatar_300x300":{
                        "height":720,
                        "uri":"2f7510004166caf1c896f",
                        "url_list":[
                            "https://p29-dy.byteimg.com/img/2f7510004166caf1c896f~c5_300x300.webp?from=4010531038",
                            "https://p26-dy.byteimg.com/img/2f7510004166caf1c896f~c5_300x300.webp?from=4010531038",
                            "https://p3-dy-ipv6.byteimg.com/img/2f7510004166caf1c896f~c5_300x300.webp?from=4010531038"
                        ],
                        "width":720
                    },
                    "avatar_larger":{
                        "height":720,
                        "uri":"2f7510004166caf1c896f",
                        "url_list":[
                            "https://p29-dy.byteimg.com/aweme/1080x1080/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p1-dy-ipv6.byteimg.com/aweme/1080x1080/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p3-dy-ipv6.byteimg.com/aweme/1080x1080/2f7510004166caf1c896f.jpeg?from=4010531038"
                        ],
                        "width":720
                    },
                    "avatar_medium":{
                        "height":720,
                        "uri":"2f7510004166caf1c896f",
                        "url_list":[
                            "https://p6-dy-ipv6.byteimg.com/aweme/720x720/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p3-dy-ipv6.byteimg.com/aweme/720x720/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p29-dy.byteimg.com/aweme/720x720/2f7510004166caf1c896f.jpeg?from=4010531038"
                        ],
                        "width":720
                    },
                    "avatar_thumb":{
                        "height":720,
                        "uri":"2f7510004166caf1c896f",
                        "url_list":[
                            "https://p26-dy.byteimg.com/aweme/100x100/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p29-dy.byteimg.com/aweme/100x100/2f7510004166caf1c896f.jpeg?from=4010531038",
                            "https://p3-dy-ipv6.byteimg.com/aweme/100x100/2f7510004166caf1c896f.jpeg?from=4010531038"
                        ],
                        "width":720
                    },
                    "avatar_uri":"2f7510004166caf1c896f",
                    "aweme_count":0,
                    "bind_phone":"",
                    "birthday":"1992-01-01",
                    "can_set_geofencing":null,
                    "cha_list":null,
                    "comment_filter_status":0,
                    "comment_setting":0,
                    "commerce_user_level":0,
                    "constellation":12,
                    "cover_url":[
                        {
                            "height":720,
                            "uri":"c8510002be9a3a61aad2",
                            "url_list":[
                                "https://p3-dy-ipv6.byteimg.com/obj/c8510002be9a3a61aad2?from=2563711402",
                                "https://p1-dy-ipv6.byteimg.com/obj/c8510002be9a3a61aad2?from=2563711402",
                                "https://p29-dy.byteimg.com/obj/c8510002be9a3a61aad2?from=2563711402"
                            ],
                            "width":720
                        }
                    ],
                    "create_time":0,
                    "custom_verify":"",
                    "cv_level":"",
                    "download_prompt_ts":0,
                    "download_setting":-1,
                    "duet_setting":0,
                    "enable_nearby_visible":true,
                    "enterprise_verify_reason":"",
                    "favoriting_count":0,
                    "fb_expire_time":0,
                    "follow_status":0,
                    "follower_count":0,
                    "follower_status":0,
                    "followers_detail":null,
                    "following_count":0,
                    "gender":2,
                    "geofencing":[
                    ],
                    "google_account":"",
                    "has_email":false,
                    "has_facebook_token":false,
                    "has_insights":false,
                    "has_orders":false,
                    "has_twitter_token":false,
                    "has_unread_story":false,
                    "has_youtube_token":false,
                    "hide_location":false,
                    "hide_search":false,
                    "homepage_bottom_toast":null,
                    "ins_id":"",
                    "is_ad_fake":false,
                    "is_binded_weibo":false,
                    "is_block":false,
                    "is_discipline_member":false,
                    "is_gov_media_vip":false,
                    "is_phone_binded":false,
                    "is_star":false,
                    "is_verified":true,
                    "item_list":null,
                    "language":"zh-Hans",
                    "live_agreement":0,
                    "live_agreement_time":0,
                    "live_commerce":false,
                    "live_verify":0,
                    "location":"",
                    "need_points":null,
                    "need_recommend":0,
                    "neiguang_shield":0,
                    "new_story_cover":null,
                    "nickname":"小仙女穿搭",
                    "platform_sync_info":null,
                    "prevent_download":false,
                    "react_setting":0,
                    "reflow_page_gid":0,
                    "reflow_page_uid":0,
                    "region":"CN",
                    "relative_users":null,
                    "room_id":0,
                    "school_name":"",
                    "school_poi_id":"",
                    "school_type":0,
                    "sec_uid":"MS4wLjABAAAAJc213DaWgkI_wekV84O-LJj9sYQBHpRtS0c_yluy-Ug",
                    "secret":0,
                    "shield_comment_notice":0,
                    "shield_digg_notice":0,
                    "shield_follow_notice":0,
                    "short_id":"2922604929",
                    "show_image_bubble":false,
                    "signature":"坚持每天上新👗
关注我，让你每天搭配不一样💗",
                    "special_lock":1,
                    "status":1,
                    "stitch_setting":0,
                    "story_count":0,
                    "story_open":false,
                    "sync_to_toutiao":0,
                    "total_favorited":0,
                    "tw_expire_time":0,
                    "twitter_id":"",
                    "twitter_name":"",
                    "type_label":null,
                    "uid":"910026647016429",
                    "unique_id":"dym1hj4c0jap",
                    "unique_id_modify_time":1600096397,
                    "user_canceled":false,
                    "user_mode":0,
                    "user_period":0,
                    "user_rate":1,
                    "user_tags":null,
                    "verification_type":1,
                    "verify_info":"",
                    "video_icon":{
                        "height":720,
                        "uri":"",
                        "url_list":[
                        ],
                        "width":720
                    },
                    "weibo_name":"",
                    "weibo_schema":"",
                    "weibo_url":"",
                    "weibo_verify":"",
                    "white_cover_url":null,
                    "with_commerce_entry":false,
                    "with_dou_entry":false,
                    "with_fusion_shop_entry":true,
                    "with_shop_entry":false,
                    "youtube_channel_id":"",
                    "youtube_channel_title":"",
                    "youtube_expire_time":0
                },
                "author_user_id":910026647016429,
                "aweme_control":{
                    "can_comment":true,
                    "can_forward":true,
                    "can_share":true,
                    "can_show_comment":true
                },
                "aweme_id":"6789912376708762888",
                "aweme_type":0,
                "bodydance_score":0,
                "challenge_position":null,
                "city":"370400",
                "cmt_swt":false,
                "collect_stat":0,
                "comment_list":null,
                "commerce_config_data":null,
                "commerce_info":{
                },
                "cover_labels":null,
                "create_time":1580899671,
                "desc":"超遮肉的春款穿搭，最后一套瘦哭你@DOU+小助手 #这么穿显瘦20斤 #2020鼠年上上签",
                "desc_language":"zh",
                "descendants":{
                    "notify_msg":"头条",
                    "platforms":[
                        "toutiao"
                    ]
                },
                "distance":"",
                "distribute_type":1,
                "duration":12667,
                "geofencing":[
                ],
                "geofencing_regions":null,
                "group_id":"6789912376708762888",
                "has_vs_entry":true,
                "have_dashboard":false,
                "hybrid_label":null,
                "image_infos":null,
                "interaction_stickers":null,
                "is_ads":false,
                "is_fantasy":false,
                "is_hash_tag":1,
                "is_pgcshow":false,
                "is_preview":0,
                "is_relieve":false,
                "is_story":0,
                "is_top":0,
                "is_vr":false,
                "item_comment_settings":0,
                "item_duet":0,
                "item_react":0,
                "item_stitch":0,
                "label_top_text":null,
                "long_video":null,
                "need_vs_entry":true,
                "nickname_position":null,
                "origin_comment_ids":null,
                "poi_patch_info":{
                    "item_patch_poi_prompt_mark":0
                },
                "position":null,
                "prevent_download":false,
                "promotion_other_info":{
                    "recall_reason":""
                },
                "promotions":[
                ],
                "rate":12,
                "region":"CN",
                "report_action":false,
                "risk_infos":{
                    "content":"",
                    "risk_sink":false,
                    "type":0,
                    "vote":false,
                    "warn":false
                },
                "share_info":{
                    "bool_persist":0,
                    "share_desc":"在抖音，记录美好生活",
                    "share_desc_info":"#在抖音，记录美好生活#超遮肉的春款穿搭，最后一套瘦哭你@DOU+小助手 #这么穿显瘦20斤 #2020鼠年上上签",
                    "share_link_desc":"超遮肉的春款穿搭，最后一套瘦哭你@DOU+小助手 #这么穿显瘦20斤 #2020鼠年上上签  %s 复制此链接，打开【抖音短视频】，直接观看视频！",
                    "share_quote":"",
                    "share_signature_desc":"",
                    "share_signature_url":"",
                    "share_title":"超遮肉的春款穿搭，最后一套瘦哭你@DOU+小助手 #这么穿显瘦20斤 #2020鼠年上上签",
                    "share_title_myself":"",
                    "share_title_other":"",
                    "share_url":"https://www.iesdouyin.com/share/video/6789912376708762888/?region=CN&mid=6789895472372665091&u_code=0&titleType=title",
                    "share_weibo_desc":"#在抖音，记录美好生活#超遮肉的春款穿搭，最后一套瘦哭你@DOU+小助手 #这么穿显瘦20斤 #2020鼠年上上签"
                },
                "share_url":"https://www.iesdouyin.com/share/video/6789912376708762888/?region=CN&mid=6789895472372665091&u_code=0&titleType=title",
                "simple_promotions":"[{"promotion_id":"61116606267400","product_id":"611166062674","title":"MIUCO重工百褶荷叶边翻领衬衫+针织马甲收腰套装女装2020春秋","price":16500,"sales":248,"elastic_images":[{"uri":"cmp-ecom-alliance/FtzDWxP5QFY8jFDs6jGZiB5xwH4t.jpg","url_list":["http://p1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FtzDWxP5QFY8jFDs6jGZiB5xwH4t.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FtzDWxP5QFY8jFDs6jGZiB5xwH4t.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FtzDWxP5QFY8jFDs6jGZiB5xwH4t.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FjWNms1xe-9VD9zQYf9sJQaO8Bxg.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjWNms1xe-9VD9zQYf9sJQaO8Bxg.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjWNms1xe-9VD9zQYf9sJQaO8Bxg.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjWNms1xe-9VD9zQYf9sJQaO8Bxg.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FpK0ti42k1MtbmviUZPemyuxWEZx.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FpK0ti42k1MtbmviUZPemyuxWEZx.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FpK0ti42k1MtbmviUZPemyuxWEZx.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FpK0ti42k1MtbmviUZPemyuxWEZx.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FrlkxRsmPcfpkIkfZHH5DQRFOsSg.jpg","url_list":["http://p9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrlkxRsmPcfpkIkfZHH5DQRFOsSg.jpg.jpeg","http://pb1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrlkxRsmPcfpkIkfZHH5DQRFOsSg.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrlkxRsmPcfpkIkfZHH5DQRFOsSg.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FkI89kEIKUuxJEpUPcasSlgZwSeY.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FkI89kEIKUuxJEpUPcasSlgZwSeY.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FkI89kEIKUuxJEpUPcasSlgZwSeY.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FkI89kEIKUuxJEpUPcasSlgZwSeY.jpg.jpeg"],"width":720,"height":720}],"promotion_source":7,"card_url":"https://aweme.snssdk.com/falcon/douyin_falcon/business/ad_card/","ies_category":2,"meta_param":"{\"is_star_atlas\":false}","goods_source":"来自淘宝"},{"promotion_id":"61039354274000","product_id":"610393542740","title":"MIUCO女人味圆领拼接星星网纱鱼尾摆荷叶边连衣裙女2020春装新款k","price":23320,"sales":1,"elastic_images":[{"uri":"cmp-ecom-alliance/Fixh3g9iynBkH9r6xhAbSdSyhL8i.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fixh3g9iynBkH9r6xhAbSdSyhL8i.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fixh3g9iynBkH9r6xhAbSdSyhL8i.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fixh3g9iynBkH9r6xhAbSdSyhL8i.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Frjd138uiMc2VxWsq_jjNXjxp42A.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Frjd138uiMc2VxWsq_jjNXjxp42A.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Frjd138uiMc2VxWsq_jjNXjxp42A.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Frjd138uiMc2VxWsq_jjNXjxp42A.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Ft2WcUPUr022gkserAJHjJy9gljZ.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Ft2WcUPUr022gkserAJHjJy9gljZ.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Ft2WcUPUr022gkserAJHjJy9gljZ.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Ft2WcUPUr022gkserAJHjJy9gljZ.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fk2t9ZYg1a8Cd52IlzNaWvEsgZzm.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fk2t9ZYg1a8Cd52IlzNaWvEsgZzm.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fk2t9ZYg1a8Cd52IlzNaWvEsgZzm.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fk2t9ZYg1a8Cd52IlzNaWvEsgZzm.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FhoGhyy0kpuAGKM36BtFfUR-HW3y.jpg","url_list":["http://p1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FhoGhyy0kpuAGKM36BtFfUR-HW3y.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FhoGhyy0kpuAGKM36BtFfUR-HW3y.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FhoGhyy0kpuAGKM36BtFfUR-HW3y.jpg.jpeg"],"width":720,"height":720}],"promotion_source":7,"card_url":"https://aweme.snssdk.com/falcon/douyin_falcon/business/ad_card/","ies_category":2,"meta_param":"{\"is_star_atlas\":false}","goods_source":"来自淘宝"},{"promotion_id":"61027341226600","product_id":"610273412266","title":"MIUCO针织马甲+复古格子领带灯笼袖衬衫裙两件套女装2020春装款k","price":26920,"sales":2,"elastic_images":[{"uri":"cmp-ecom-alliance/FsZkMba_ZD2TXSyEz-ma5uSfWh77.jpg","url_list":["http://p9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FsZkMba_ZD2TXSyEz-ma5uSfWh77.jpg.jpeg","http://pb1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FsZkMba_ZD2TXSyEz-ma5uSfWh77.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FsZkMba_ZD2TXSyEz-ma5uSfWh77.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FgcSl3VO0wmiFhGpXthnp80frM9y.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgcSl3VO0wmiFhGpXthnp80frM9y.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgcSl3VO0wmiFhGpXthnp80frM9y.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgcSl3VO0wmiFhGpXthnp80frM9y.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fhxb59OiITclZy-oanERScL0W9Kr.jpg","url_list":["http://p1.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fhxb59OiITclZy-oanERScL0W9Kr.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fhxb59OiITclZy-oanERScL0W9Kr.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fhxb59OiITclZy-oanERScL0W9Kr.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FgyPuanIL9gSeaUNwfPdbVcac7SV.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgyPuanIL9gSeaUNwfPdbVcac7SV.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgyPuanIL9gSeaUNwfPdbVcac7SV.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgyPuanIL9gSeaUNwfPdbVcac7SV.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FmRE6kpv-1iOaKv72JiIrbFzSrig.jpg","url_list":["http://p9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FmRE6kpv-1iOaKv72JiIrbFzSrig.jpg.jpeg","http://pb1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FmRE6kpv-1iOaKv72JiIrbFzSrig.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FmRE6kpv-1iOaKv72JiIrbFzSrig.jpg.jpeg"],"width":720,"height":720}],"promotion_source":7,"card_url":"https://aweme.snssdk.com/falcon/douyin_falcon/business/ad_card/","ies_category":2,"meta_param":"{\"is_star_atlas\":false}","goods_source":"来自淘宝"},{"promotion_id":"61079460198100","product_id":"610794601981","title":"MIUCO法式小马印花收腰显瘦时尚气质百褶裙连衣裙女2020早春k","price":24220,"sales":2,"elastic_images":[{"uri":"cmp-ecom-alliance/FrzhyDysoCnKUyfjMQndwHbN9nOL.jpg","url_list":["http://p1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrzhyDysoCnKUyfjMQndwHbN9nOL.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrzhyDysoCnKUyfjMQndwHbN9nOL.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrzhyDysoCnKUyfjMQndwHbN9nOL.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FvTUhiIKxhgBVgjOABJA49ATRiJb.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FvTUhiIKxhgBVgjOABJA49ATRiJb.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FvTUhiIKxhgBVgjOABJA49ATRiJb.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FvTUhiIKxhgBVgjOABJA49ATRiJb.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FrtwORimZ6ejrJNw-n80B-D6EHcr.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrtwORimZ6ejrJNw-n80B-D6EHcr.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrtwORimZ6ejrJNw-n80B-D6EHcr.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FrtwORimZ6ejrJNw-n80B-D6EHcr.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fn1P4vRt0yZYalX74pBXYTqIlpb_.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fn1P4vRt0yZYalX74pBXYTqIlpb_.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fn1P4vRt0yZYalX74pBXYTqIlpb_.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fn1P4vRt0yZYalX74pBXYTqIlpb_.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FgXZeDGXHd1so58poxjV72nlKb_u.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgXZeDGXHd1so58poxjV72nlKb_u.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgXZeDGXHd1so58poxjV72nlKb_u.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FgXZeDGXHd1so58poxjV72nlKb_u.jpg.jpeg"],"width":720,"height":720}],"promotion_source":7,"card_url":"https://aweme.snssdk.com/falcon/douyin_falcon/business/ad_card/","ies_category":2,"meta_param":"{\"is_star_atlas\":false}","goods_source":"来自淘宝"},{"promotion_id":"61121574681700","product_id":"611215746817","title":"MIUCO御姐范儿立领钉珠打缆袖口收腰大摆碎花裙女装2020春秋新款k","price":25120,"sales":8,"elastic_images":[{"uri":"cmp-ecom-alliance/Fo5hZiAmD9-vhj3m_K6OvEApRnRk.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fo5hZiAmD9-vhj3m_K6OvEApRnRk.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fo5hZiAmD9-vhj3m_K6OvEApRnRk.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fo5hZiAmD9-vhj3m_K6OvEApRnRk.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fsb8EZCP4-hn24Mb7hbkxE315HsO.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fsb8EZCP4-hn24Mb7hbkxE315HsO.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fsb8EZCP4-hn24Mb7hbkxE315HsO.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fsb8EZCP4-hn24Mb7hbkxE315HsO.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fr-ErqcFJVwUrlT8pLPLaJSmOgpS.jpg","url_list":["http://p3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-ErqcFJVwUrlT8pLPLaJSmOgpS.jpg.jpeg","http://pb9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-ErqcFJVwUrlT8pLPLaJSmOgpS.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-ErqcFJVwUrlT8pLPLaJSmOgpS.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/Fr-C1S6YSk_ATBdR9NxWeBO4oi-E.jpg","url_list":["http://p9.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-C1S6YSk_ATBdR9NxWeBO4oi-E.jpg.jpeg","http://pb1.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-C1S6YSk_ATBdR9NxWeBO4oi-E.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/Fr-C1S6YSk_ATBdR9NxWeBO4oi-E.jpg.jpeg"],"width":720,"height":720},{"uri":"cmp-ecom-alliance/FjbbHcvDIGbKUjxxCDqWmb1y8SaX.jpg","url_list":["http://p9.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjbbHcvDIGbKUjxxCDqWmb1y8SaX.jpg.jpeg","http://pb1.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjbbHcvDIGbKUjxxCDqWmb1y8SaX.jpg.jpeg","http://pb3.pstatp.com/aweme/720x720/cmp-ecom-alliance/FjbbHcvDIGbKUjxxCDqWmb1y8SaX.jpg.jpeg"],"width":720,"height":720}],"promotion_source":7,"card_url":"https://aweme.snssdk.com/falcon/douyin_falcon/business/ad_card/","ies_category":2,"meta_param":"{\"is_star_atlas\":false}","goods_source":"来自淘宝"}]",
                "sort_label":"",
                "statistics":{
                    "aweme_id":"6789912376708762888",
                    "comment_count":468,
                    "digg_count":6751,
                    "download_count":141,
                    "forward_count":23,
                    "lose_comment_count":0,
                    "lose_count":0,
                    "play_count":0,
                    "share_count":145,
                    "whatsapp_share_count":0
                },
                "status":{
                    "allow_comment":true,
                    "allow_share":true,
                    "aweme_id":"6789912376708762888",
                    "dont_share_status":-1,
                    "download_status":0,
                    "in_reviewing":false,
                    "is_delete":false,
                    "is_private":false,
                    "is_prohibited":false,
                    "private_status":0,
                    "review_result":{
                        "review_status":0
                    },
                    "reviewed":1,
                    "self_see":false,
                    "video_hide_search":0,
                    "with_fusion_goods":true,
                    "with_goods":true
                },
                "story_ttl":0,
                "text_extra":[
                    {
                        "end":24,
                        "sec_uid":"MS4wLjABAAAAfLsItSD2WiJrsji1g_iZv-it6W2CcvBFkdUwMjTeSD4",
                        "start":16,
                        "type":0,
                        "user_id":"70258503077"
                    },
                    {
                        "end":34,
                        "hashtag_id":"1636758346583044",
                        "hashtag_name":"这么穿显瘦20斤",
                        "is_commerce":false,
                        "start":25,
                        "type":1
                    },
                    {
                        "end":45,
                        "hashtag_id":"1654958136870920",
                        "hashtag_name":"2020鼠年上上签",
                        "is_commerce":false,
                        "start":35,
                        "type":1
                    }
                ],
                "uniqid_position":null,
                "user_digged":0,
                "video":{
                    "animated_cover":{
                        "uri":"tos-cn-p-0015/aff71e1f6f1c496a938cb1940813786c_1580899676",
                        "url_list":[
                            "https://p26-dy.byteimg.com/obj/tos-cn-p-0015/aff71e1f6f1c496a938cb1940813786c_1580899676?from=2563711402_large",
                            "https://p29-dy.byteimg.com/obj/tos-cn-p-0015/aff71e1f6f1c496a938cb1940813786c_1580899676?from=2563711402_large",
                            "https://p6-dy-ipv6.byteimg.com/obj/tos-cn-p-0015/aff71e1f6f1c496a938cb1940813786c_1580899676?from=2563711402_large"
                        ]
                    },
                    "big_thumbs":null,
                    "bit_rate":[
                        {
                            "bit_rate":1476364,
                            "gear_name":"normal_540",
                            "is_bytevc1":0,
                            "is_h265":0,
                            "play_addr":{
                                "data_size":2337639,
                                "file_cs":"c:0-15163-8a20",
                                "height":720,
                                "uri":"v0200ff70000bot9qkt1mike03m89rn0",
                                "url_key":"v0200ff70000bot9qkt1mike03m89rn0_h264_540p_1476364",
                                "url_list":[
                                    "http://v95-dy.ixigua.com/46ff7b126230f2dd2d9705c1d564ba13/5f5f96a9/video/tos/cn/tos-cn-ve-15/ed3d524afc414fd5b3c3e03b799f89b6/?a=1128&br=4323&bt=1441&cr=0&cs=0&cv=1&dr=0&ds=6&er=&l=2020091423131701012912923017205465&lr=all&mime_type=video_mp4&qs=0&rc=M3U7NmhsNG48cjMzOmkzM0ApaWRoZTZmZ2VoNzhmO2ZlZ2drNmotaGpxbnFfLS1jLS9zcy9eNi4vNF8wMjUzMWItMC46Yw%3D%3D&vl=&vr=",
                                    "http://v6-dy.ixigua.com/ce6ce97ff61b4e16b855254ae7be4dab/5f5f96a9/video/tos/cn/tos-cn-ve-15/ed3d524afc414fd5b3c3e03b799f89b6/?a=1128&br=4323&bt=1441&cr=0&cs=0&cv=1&dr=0&ds=6&er=&l=2020091423131701012912923017205465&lr=all&mime_type=video_mp4&qs=0&rc=M3U7NmhsNG48cjMzOmkzM0ApaWRoZTZmZ2VoNzhmO2ZlZ2drNmotaGpxbnFfLS1jLS9zcy9eNi4vNF8wMjUzMWItMC46Yw%3D%3D&vl=&vr=",
                                    "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=0&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED",
                                    "https://api.amemv.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=1&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED"
                                ],
                                "width":720
                            },
                            "quality_type":20
                        }
                    ],
                    "cdn_url_expired":0,
                    "cover":{
                        "height":720,
                        "uri":"tos-cn-p-0015/f3bdc9a9137e41deb84b409c07385619_1580899676",
                        "url_list":[
                            "https://p26-dy.byteimg.com/img/tos-cn-p-0015/f3bdc9a9137e41deb84b409c07385619_1580899676~c5_300x400.jpeg?from=2563711402_large",
                            "https://p9-dy.byteimg.com/img/tos-cn-p-0015/f3bdc9a9137e41deb84b409c07385619_1580899676~c5_300x400.jpeg?from=2563711402_large",
                            "https://p6-dy-ipv6.byteimg.com/img/tos-cn-p-0015/f3bdc9a9137e41deb84b409c07385619_1580899676~c5_300x400.jpeg?from=2563711402_large"
                        ],
                        "width":720
                    },
                    "download_addr":{
                        "data_size":2337639,
                        "height":720,
                        "uri":"v0200ff70000bot9qkt1mike03m89rn0",
                        "url_list":[
                            "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=aweme&source=PackSourceEnum_ECOMMERCE_FEED",
                            "https://api.amemv.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=1&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=aweme&source=PackSourceEnum_ECOMMERCE_FEED"
                        ],
                        "width":720
                    },
                    "download_suffix_logo_addr":{
                        "height":720,
                        "uri":"v0200ff70000bot9qkt1mike03m89rn0",
                        "url_list":[
                            "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=aweme_suffix&source=PackSourceEnum_ECOMMERCE_FEED",
                            "https://api.amemv.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=1&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=aweme_suffix&source=PackSourceEnum_ECOMMERCE_FEED"
                        ],
                        "width":720
                    },
                    "duration":12667,
                    "dynamic_cover":{
                        "height":720,
                        "uri":"tos-cn-p-0015/29044707ddaf4a27a6ab69518cfb829d_1580899676",
                        "url_list":[
                            "https://p3-dy-ipv6.byteimg.com/obj/tos-cn-p-0015/29044707ddaf4a27a6ab69518cfb829d_1580899676?from=2563711402_large",
                            "https://p9-dy.byteimg.com/obj/tos-cn-p-0015/29044707ddaf4a27a6ab69518cfb829d_1580899676?from=2563711402_large",
                            "https://p6-dy-ipv6.byteimg.com/obj/tos-cn-p-0015/29044707ddaf4a27a6ab69518cfb829d_1580899676?from=2563711402_large"
                        ],
                        "width":720
                    },
                    "has_download_suffix_logo_addr":true,
                    "has_watermark":true,
                    "height":960,
                    "is_bytevc1":0,
                    "is_callback":true,
                    "is_h265":0,
                    "need_set_token":false,
                    "origin_cover":{
                        "height":720,
                        "uri":"tos-cn-p-0015/0334e9d10d214b5090dce9c941c8e714_1580899676",
                        "url_list":[
                            "https://p9-dy.byteimg.com/tos-cn-p-0015/0334e9d10d214b5090dce9c941c8e714_1580899676~tplv-dy-360p.jpeg?from=2563711402",
                            "https://p26-dy.byteimg.com/tos-cn-p-0015/0334e9d10d214b5090dce9c941c8e714_1580899676~tplv-dy-360p.jpeg?from=2563711402",
                            "https://p29-dy.byteimg.com/tos-cn-p-0015/0334e9d10d214b5090dce9c941c8e714_1580899676~tplv-dy-360p.jpeg?from=2563711402"
                        ],
                        "width":720
                    },
                    "play_addr":{
                        "data_size":2337639,
                        "file_cs":"c:0-15163-8a20",
                        "height":720,
                        "uri":"v0200ff70000bot9qkt1mike03m89rn0",
                        "url_key":"v0200ff70000bot9qkt1mike03m89rn0_h264_540p_1476364",
                        "url_list":[
                            "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=0&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED",
                            "https://api.amemv.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=1&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED"
                        ],
                        "width":720
                    },
                    "play_addr_lowbr":{
                        "data_size":2337639,
                        "file_cs":"c:0-15163-8a20",
                        "height":720,
                        "uri":"v0200ff70000bot9qkt1mike03m89rn0",
                        "url_key":"v0200ff70000bot9qkt1mike03m89rn0_h264_540p_1476364",
                        "url_list":[
                            "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=0&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED",
                            "https://api.amemv.com/aweme/v1/play/?video_id=v0200ff70000bot9qkt1mike03m89rn0&line=1&ratio=540p&media_type=4&vr_type=0&improve_bitrate=0&is_play_url=1&source=PackSourceEnum_ECOMMERCE_FEED"
                        ],
                        "width":720
                    },
                    "ratio":"540p",
                    "tags":null,
                    "use_static_cover":false,
                    "width":540
                },
                "video_control":{
                    "allow_download":true,
                    "allow_duet":true,
                    "allow_dynamic_wallpaper":true,
                    "allow_music":true,
                    "allow_react":true,
                    "allow_stitch":true,
                    "draft_progress_bar":0,
                    "prevent_download_type":0,
                    "share_type":1,
                    "show_progress_bar":0,
                    "timer_status":1
                },
                "video_labels":null,
                "video_text":[
                ],
                "vr_type":0,
                "with_promotional_music":false,
                "without_watermark":false,
                "xigua_task":{
                    "is_xigua_task":false
                }
            }
        ],
        "similar_list":[
        ],
        "status_code":0
    },
    "msg":"success"
}
```


