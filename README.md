jQuery if {} else {}
===
jquery 判斷事件


#### 判斷事件是否存在 - 如果存在
~~~
if($('#ABC').data(dtScroll).length){
	// 如果存在 執行下列動作
	dtScroll.destroy();
	$('#ABC').off();
	$('#ABC_scroller').off().removeAttr('style');
}
~~~

#### JavaScript - 判斷某個 ID 是否擁有 某個 CLASS, .hasClass('CLASS')
~~~
if ($('#ABC').hasClass('CLASS')){
}
~~~

#### JavaScript - 判斷某個CSS 是否擁符合條件
~~~
if($('#ABC').css("display")!=="none"){
}

if($('#ABC').css("display")==="block"){
}
~~~

#### JavaScript - 判斷欄位存在與否 .length
~~~
if ($('#TEST').length){
	// 此欄位存在的時候
	alert('#TEST');
}
~~~
