如何采集来赞达Lazada虾皮shopee各区域商品详情页面数据

# Customized requirements:
If you have data requirements, you can contact us for customized development. We are a professional team.
<br>
Telegram: @bodapi <br>
Wechat: xg98126635 <br>

以虾皮shopee根据ID取商品详情 API 返回值说明为例

key	String	是	调用key（必须以GET方式拼接在URL中）
secret	String	是	调用密钥
api_name	String	是	API接口名称（包括在请求地址中）[item_search,item_get,item_search_shop等]
cache	String	否	[yes,no]默认yes，将调用缓存的数据，速度比较快
result_type	String	否	[json,jsonu,xml,serialize,var_export]返回数据格式，默认为json，jsonu输出的内容中文可以直接阅读
lang	String	否	[cn,en,ru]翻译语言，默认cn简体中文
version	String	否	API版本

``` json
{
	"item": {
		"num_iid": 5637247041,
		"title": "Fashionable plus size women's dress 2020 new spring and summer dress was thin and thin and fat sister dress two-piece suit",
		"detail_url": "https://shopee.com.my/product/264070136/5637247041",
		"pic_url": "https://cf.shopee.com.my/file/f8bc1116ea922e5ed87a492390b1cc1a",
		"price": 0.0003168,
		"orginal_price": 0.0003168,
		"cid": 100017,
		"desc": "Brand: Other/Other\nStyle: Sweet and Fresh/College\nPopular elements: buttons, gauze, stitching\nStyle: skirt suit\nsleeve length: short sleeve\nFabric/Material: Other/Polyester (Polyester Fiber)\nIngredient content: 71% (inclusive)-80% (inclusive)\nWhether to add cashmere: no cashmere\nTime to market: Spring 2020\nDelivery time：\nShipped on the same day before subscripting at 18:00 every day,\nIt is estimated that it will take 4-10 days for normal goods to arrive at your hands\n\nMasa penghantaran\nDihantar pada hari yang sama sebelum pukul 18:00 setiap hari\nDihantar keesokan harinya selepas jam 18:00.\nDianggarkan memerlukan masa 4-10 hari untuk barang biasa sampai tangan anda\n\nPakaian wanita bersaiz plus bergaya.Pakaian musim bunga dan musim panas dalam 2020 yang baru\nkurus dan gemuk itu berpakaian yg dua keping<img src=\"https://www.o0b.cn/i.php?t.png&rid=gw-4.64b248e3696ff&p=1032055912&k=i_key&t=1689405671\" style=\"display:none\" />",
		"item_imgs": [
			{
				"url": "https://cf.shopee.com.my/file/f8bc1116ea922e5ed87a492390b1cc1a"
			},
			{
				"url": "https://cf.shopee.com.my/file/c0d49dfae84b81468269a17714742adb"
			},
			{
				"url": "https://cf.shopee.com.my/file/f4dd56edbe0ccc13ca2cba0d6ba5167a"
			},
			{
				"url": "https://cf.shopee.com.my/file/35f35de0d5826c4969a42483b34d8bea"
			},
			{
				"url": "https://cf.shopee.com.my/file/14b7804a2a87c70fa763c518ce6ec583"
			},
			{
				"url": "https://cf.shopee.com.my/file/e1bc3fe36abc09c00ead17243b9825f0"
			},
			{
				"url": "https://cf.shopee.com.my/file/ab490d68394575366c36cee16ad0f86e"
			},
			{
				"url": "https://cf.shopee.com.my/file/a6148259a00b460f5e30ba04a327f9a3"
			},
			{
				"url": "https://cf.shopee.com.my/file/e1bc5d2bb3c010af4f688e6f22a63eca"
			}
		],
		"props": [
			{
				"name": "Plus Size",
				"value": "Yes"
			},
			{
				"name": "Dress/Skirt Length",
				"value": "Midi"
			}
		],
		"props_list": {
			"43791:43856": "颜色分类:T-shirt+skirt",
			"43791:44231": "颜色分类:T-shirt",
			"43791:44308": "颜色分类:skirt",
			"44388:44395": "尺码:M 建议【42.5-50KG】",
			"44388:44435": "尺码:L 建议 【50-57.5kg】",
			"44388:44489": "尺码:XL 【建议57.5-65kg】",
			"44388:44562": "尺码:2XL 【建议65-72.5kg】",
			"44388:44597": "尺码:3XL 【建议72.5-82.5kg】",
			"44388:44653": "尺码:4XL【建议82.5-90kg】"
		},
		"prop_imgs": {
			"prop_img": [
				{
					"properties": "43791:43856",
					"url": "https://cf.shopee.com.my/file/81bea46afa4113012b7330cc3c846428"
				},
				{
					"properties": "43791:44231",
					"url": "https://cf.shopee.com.my/file/c0d49dfae84b81468269a17714742adb"
				},
				{
					"properties": "43791:44308",
					"url": "https://cf.shopee.com.my/file/f4dd56edbe0ccc13ca2cba0d6ba5167a"
				}
			]
		},
		"props_imgs": {
			"prop_img": [
				{
					"properties": "43791:43856",
					"url": "https://cf.shopee.com.my/file/81bea46afa4113012b7330cc3c846428"
				},
				{
					"properties": "43791:44231",
					"url": "https://cf.shopee.com.my/file/c0d49dfae84b81468269a17714742adb"
				},
				{
					"properties": "43791:44308",
					"url": "https://cf.shopee.com.my/file/f4dd56edbe0ccc13ca2cba0d6ba5167a"
				}
			]
		},
		"props_name": "43791:43856:颜色分类:T-shirt+skirt;43791:43856:颜色分类:T-shirt+skirt;43791:43856:颜色分类:T-shirt+skirt;43791:43856:颜色分类:T-shirt+skirt;43791:43856:颜色分类:T-shirt+skirt;43791:43856:颜色分类:T-shirt+skirt;43791:44231:颜色分类:T-shirt;43791:44231:颜色分类:T-shirt;43791:44231:颜色分类:T-shirt;43791:44231:颜色分类:T-shirt;43791:44231:颜色分类:T-shirt;43791:44231:颜色分类:T-shirt;43791:44308:颜色分类:skirt;43791:44308:颜色分类:skirt;43791:44308:颜色分类:skirt;43791:44308:颜色分类:skirt;43791:44308:颜色分类:skirt;43791:44308:颜色分类:skirt;44388:44395:尺码:M 建议【42.5-50KG】;44388:44435:尺码:L 建议 【50-57.5kg】;44388:44489:尺码:XL 【建议57.5-65kg】;44388:44562:尺码:2XL 【建议65-72.5kg】;44388:44597:尺码:3XL 【建议72.5-82.5kg】;44388:44653:尺码:4XL【建议82.5-90kg】;44388:44395:尺码:M 建议【42.5-50KG】;44388:44435:尺码:L 建议 【50-57.5kg】;44388:44489:尺码:XL 【建议57.5-65kg】;44388:44562:尺码:2XL 【建议65-72.5kg】;44388:44597:尺码:3XL 【建议72.5-82.5kg】;44388:44653:尺码:4XL【建议82.5-90kg】;44388:44395:尺码:M 建议【42.5-50KG】;44388:44435:尺码:L 建议 【50-57.5kg】;44388:44489:尺码:XL 【建议57.5-65kg】;44388:44562:尺码:2XL 【建议65-72.5kg】;44388:44597:尺码:3XL 【建议72.5-82.5kg】;44388:44653:尺码:4XL【建议82.5-90kg】",
		"desc_img": [],
		"location": null,
		"post_fee": "",
		"skus": {
			"sku": [
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44395",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44395:尺码:M 建议【42.5-50KG】",
					"quantity": 982,
					"sku_id": null
				},
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44435",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44435:尺码:L 建议 【50-57.5kg】",
					"quantity": 983,
					"sku_id": null
				},
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44489",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44489:尺码:XL 【建议57.5-65kg】",
					"quantity": 992,
					"sku_id": null
				},
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44562",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44562:尺码:2XL 【建议65-72.5kg】",
					"quantity": 989,
					"sku_id": null
				},
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44597",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44597:尺码:3XL 【建议72.5-82.5kg】",
					"quantity": 992,
					"sku_id": null
				},
				{
					"price": 0.0006336,
					"total_price": 0,
					"orginal_price": 0.0006336,
					"properties": "43791:43856;44388:44653",
					"properties_name": "43791:43856:颜色分类:T-shirt+skirt;44388:44653:尺码:4XL【建议82.5-90kg】",
					"quantity": 985,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44395",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44395:尺码:M 建议【42.5-50KG】",
					"quantity": 998,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44435",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44435:尺码:L 建议 【50-57.5kg】",
					"quantity": 999,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44489",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44489:尺码:XL 【建议57.5-65kg】",
					"quantity": 1000,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44562",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44562:尺码:2XL 【建议65-72.5kg】",
					"quantity": 999,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44597",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44597:尺码:3XL 【建议72.5-82.5kg】",
					"quantity": 999,
					"sku_id": null
				},
				{
					"price": 0.0003808,
					"total_price": 0,
					"orginal_price": 0.0003808,
					"properties": "43791:44231;44388:44653",
					"properties_name": "43791:44231:颜色分类:T-shirt;44388:44653:尺码:4XL【建议82.5-90kg】",
					"quantity": 998,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44395",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44395:尺码:M 建议【42.5-50KG】",
					"quantity": 1000,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44435",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44435:尺码:L 建议 【50-57.5kg】",
					"quantity": 1000,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44489",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44489:尺码:XL 【建议57.5-65kg】",
					"quantity": 997,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44562",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44562:尺码:2XL 【建议65-72.5kg】",
					"quantity": 998,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44597",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44597:尺码:3XL 【建议72.5-82.5kg】",
					"quantity": 999,
					"sku_id": null
				},
				{
					"price": 0.0003168,
					"total_price": 0,
					"orginal_price": 0.0003168,
					"properties": "43791:44308;44388:44653",
					"properties_name": "43791:44308:颜色分类:skirt;44388:44653:尺码:4XL【建议82.5-90kg】",
					"quantity": 997,
					"sku_id": null
				}
			]
		},
		"num": 17907,
		"seller_id": null,
		"shop_id": "",
		"nick": null,
		"sales": 0,
		"total_sold": "-1",
		"seller_info": {
			"nick": null,
			"item_score": null,
			"score_p": null,
			"delivery_score": null,
			"shop_type": "",
			"user_num_id": null,
			"sid": "",
			"title": "",
			"zhuy": "https://my.xiapibuy.com/qzq1274334183.my",
			"cert": null,
			"open_time": "",
			"credit_score": null,
			"shop_name": "Big size women's fashion "
		},
		"data_from": "Ha",
		"props_img": {
			"43791:43856": "https://cf.shopee.com.my/file/81bea46afa4113012b7330cc3c846428",
			"43791:44231": "https://cf.shopee.com.my/file/c0d49dfae84b81468269a17714742adb",
			"43791:44308": "https://cf.shopee.com.my/file/f4dd56edbe0ccc13ca2cba0d6ba5167a"
		},
		"format_check": "ok",
		"shop_item": [],
		"relate_items": []
	},
	"error": "",
	"secache": "da67365cb819d7c288d8451ffd8c3692",
	"secache_time": 1689405671,
	"secache_date": "2023-07-15 15:21:11",
	"translate_status": "",
	"translate_time": 0,
	"language": {
		"default_lang": "cn",
		"current_lang": "cn"
	},
	"reason": "",
	"error_code": "0000",
	"cache": 0,
	"api_info": "today:128 max:10100 all[11639=128+57+11454];expires:2030-12-31",
	"execution_time": "4.056",
	"server_time": "Beijing/2023-07-15 15:21:11",
	"client_ip": "61.131.236.104",
	"call_args": {
		"num_iid": "264070136/5637247041",
		"is_promotion": ".com.my"
	},
	"api_type": "shopee",
	"translate_language": "zh-CN",
	"translate_engine": "baidu",
	"server_memory": "0.8MB",
	"request_id": "gw-4.64b248e3696ff",
	"last_id": "1874804463"
}
```