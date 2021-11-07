

if($text == 'المطور' || $text == 'مطور'){ 

bot('sendphoto',[

'chat_id'=>$chat_id,

photo =>"https://t.me/",

'caption'=>'

اضغط علي الزر .

', 

'parse_mode'=>"markdown",'disable_web_page_preview'=>true,

"reply_markup"=>json_encode([

"inline_keyboard"=>[

[['text'=>'DEV','url'=>'t.me/']], 

[['text'=>"اضف البوت لمجموعتك",'url'=>'https://telegram.me/يوزر البوت?startgroup=start']],

]

])

]);

}
