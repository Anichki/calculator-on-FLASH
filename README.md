calculator-on-FLASH
===================

Algoritm of calculator on AS3

var რეზულტატის ცვლადი:Number = new Number;

ღილაკის სახელი.addEventListener(MouseEvent.MOUSE_OVER, ფუნქციის სახელი);
ღილაკის სახელი.addEventListener(MouseEvent.MOUSE_OUT,  ფუნქციის სახელი);
ღილაკის სახელი.addEventListener(MouseEvent.CLICK,  ფუნქციის სახელი);
ღილაკის სახელი.buttonMode = true;


function ფუნქციის სახელი (event:MouseEvent):void {

ფუნქციის პირობა;

  trace(event.type);
	}

	
	if (isNaN(Number(ტექსტუალური ჩარჩოს სახელი.text))) {

	} else if (isNaN(Number(ტექსტუალური ჩარჩოს სახელი.text))) {
		
	} else {
	
	
	
	რეზულტატის ცვლადი = მათემატიკური ოპერაცია;
	

	trace(event.type);
	
	}
	
	}
	
	
	
===================	
ტექსტუალური ჩარჩო
	
	
	//Red+
var myTextFormat_red:TextFormat = new TextFormat();
myTextFormat_red.font = "_sans";
myTextFormat_red.size = 14;
myTextFormat_red.color = "0xff0000";
//Red-
//TextFormat -


//Current Mode +
var Current_Mode:TextField = new TextField ();
Current_Mode.wordWrap = true;
Current_Mode.width = 120;
Current_Mode.height = 30;
// myTextField.border = true;
Current_Mode.x = 26;
Current_Mode.y = 70;
Current_Mode.selectable = false;

Current_Mode.defaultTextFormat = myTextFormat_red;

addChild(Current_Mode);
Current_Mode.htmlText = "Current Mode";
//Current Mode +