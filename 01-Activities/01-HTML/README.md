# 01-HTML 

## ကျောင်းသားတစ်ယောက်၏ ကိုယ်ရေး အချက်အလက်ကို ရေးသားခြင်း။

* မာတိကာ 
အခန်း ၁။ Title ။ 
အခန်း ၂။ header ။ 
အခန်း ၃။ section 1/2။ 

# အခန်း ၁။ Title ။ 

* Title ကို Student Bio လို့ နာမည်ပေးထားပါတယ်။ ဒီနာမည်က web browser ရဲ့ title bar မှာ Student Bio လို့ ပေါ်နေမှာပါ။

# ပြုလုပ်ရန်။

* head tag ထဲမှာ title tag ကို ရေးပါ။ title tag ထဲမှာ student Bio ဆိုပြီး ရေးရပါမယ်။
* အောက်ပါ ပုံစံလေးပါပဲ။
<head>
    <meta charset="UTF-8">
    <title>Student Bio</title>
</head>

# အခန်း ၂။ header ။ 

* ခေါင်းစဥ်ကြီးတွေကို ရေးသားလိုတဲ့အခါ header tag h1 နဲ့ ရေးသားရပါတယ်။

# ပြုလုပ်ရန်။

* body ထဲမှာ header tag ကို ရေးပါ။ header tag ထဲမှာ h1 tag ကို h1 ထဲမှာ student Bio ကို ရေးပါ။ အောက်ပါပုံစံလေးကို တွေ့ရပါမယ်။။
<body>
 <header>
      <h1>Student Bio</h1>
 </header>
</body>

# အခန်း ၃။ section 1/2။ 
# section 1။
* section 1 မှာ ကျောင်းသားရဲ့ နာမည်ကို ရေးရပါတယ်။ ဓါတ်ပုံထည့်ရပါတယ်။ ကျောင်းသားရဲ့ ကိုယ်ရေးရာဇဝင် အချက်အလက် ထည့်ရေးရပါတယ်။

# ပြုလုပ်ရန်။

* body ထဲမှာ section tag ကို ရေးပါ။ section tag ထဲမှာ ၁။ h2 tag ကို ရေးပါ။ h2 tag ထဲမှာ ကျောင်းသား နာမည်။ ၂။ img tag ကို ရေးပါ။ img tag ထဲမှာ ဓါတ်ပုံ လင့်ထည့်ပါ။  p tag ကို ရေးပါ။ p tag ထဲမှာ ကျောင်းသားရဲ့ ကိုယ်ရေး အချက်အလက် အကြောင်းအရာကို ရေးပါ။
* အောက်ပါ ပုံစံကို မြင်တွေ့ရပါလိမ်ံမယ်။
<body>
<section>
      <h2>Agganyana</h2>
      <img src="assets/agga.jpg" alt="Agganyana">
      <p>I was born in kachin state, Moe Hnyin township and my village is Nanwin kone</p>
</section>
</body>

# section 2။

* section 2 မှာတော့ ကျောင်းသားတစ်ယောက်ရဲ့ ဆက်သွယ်မှုကို သတ်မှတ်ပေးထားပါတယ်။ gmail. github. portfolio လင့်တွေ လုပ်ထားပါတယ်။ ဒီလုပ်တဲ့အခါမှာ ul = unorderlist. li = list item. strong tag.  a tag တွေ သုံးထားပါတယ်။ 

# ပြုလုပ်ရန်။

* body ထဲမှာ section tag ကို ရေးခဲ့တဲ့ အတိုင်း ၁။ h2 tag ကို ရေးပါ။ h2 tag ထဲမှာ contact info ကို ရေးပါ။ အဲ့ဒီနောက်မှာ ul tag၊ ul tag ထဲမှာ li tag၊ li tag ထဲမှာ strong tag၊ တွေကို အစဥ်အတိုင်း ရေးပါတယ်။ gmail. github. portfolio လင့်တွေ ထည့်ပါတယ်။ 
အောက်ပါ ပုံစံကို ကြည့်ပါ။

 <section>
      <h2>Contact Info</h2>
      <ul>
        <li။<strong>Email:</strong> <a href="http://agganyana3@gmail.com">agganyana3@gmail.com</a></li>
        <li><strong>GitHub:</strong> <a href="https://github.com/Min-Ya-Nant/Module-1.git">min-ya-nant</a></li>
        <li><strong>Portfolio:</strong> <a href="https://min-ya-nant.github.io/portfolio/">Portfolio</a></li>
      </ul>
</section>

# အထူး အထူး မှာကြားချက်။

* ဓါတ်ပုံထည့်တဲ့အခါမှာ width, height မထည့်ပဲ ဒီအတိုင်း ထည့်လိုက်ရင် ဓါတ်ပုံက အရမ်းကြီးနေတတ်ပါတယ်။
index.html ထဲမှာပဲ inline style နဲ့ width, height ရေးထည့်မှ ဆရာတွေ ပေးထားတဲ့ ညွန်ကြားချက် အတိုင်း အံဝင်ခွင်ကျ လှလှပပ ဖြစ်သွားပါမယ်။
ဒီပုံစံလေးကို ထည့်ရေးဖြစ်အောင် ရေးလိုက်ပါ။

 <style>
        img {
          width: 200px;
          height: 200px;
        }
       </style>

    နောက်ဆုံးမှာ ဒီလို ပုံစံကို မြင်တွေ့ကြရပါမယ်။

    ![alt text](<Screenshot from 2024-07-08 18-21-23.png>)

