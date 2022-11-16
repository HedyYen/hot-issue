# search
<?php 
	$arr = [
		[
			"title"=>"俗女養成日記",
			"num"=>101,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		],
		[
			"title"=>"五月天演唱會",
			"num"=>145,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"蔡依林小巨蛋售票系統",
			"num"=>234,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"美元匯率重回30",
			"num"=>156,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"如果我在日本永遠到不了捷運",
			"num"=>89,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"夜市吃甚麼",
			"num"=>99,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"魔獸來台",
			"num"=>101,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]
		,
		[
			"title"=>"林志穎回歸",
			"num"=>210,
			"url"=>"https://www.google.com.tw/?hl=zh_TW"
		]

	];

	
	//随机排序数组 
	shuffle($arr); 
	
	echo json_encode($arr);
	
