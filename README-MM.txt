Dino Hunter Web - Android APK build

ဒီ project က https://comdh.krig.games/ ကို Android app (WebView) ထဲမှာဖွင့်ပေးတဲ့ wrapper ဖြစ်ပါတယ်။ မူရင်း game ကို APK အဖြစ်ပြောင်းထားတာ မဟုတ်ပါ။ Game website က online ရှိနေရပါမယ်။ Save ကို website ဘက်က ခွင့်ပြု/ထိန်းသိမ်းပေးမှုအပေါ် မူတည်ပြီး ဒီ app က save မဖြစ်တာကို အာမမခံနိုင်ပါ။

APK ထုတ်ရန် GitHub Actions သုံးပါ:
1. GitHub account နဲ့ login ဝင်ပါ။
2. New repository ဖန်တီးပါ (ဥပမာ dino-hunter-web-app)။ Public သို့မဟုတ် Private နှစ်မျိုးလုံးရပါတယ်။
3. ဒီ ZIP ကို ဖုန်း/ကွန်ပျူတာမှာ extract လုပ်ပါ။
4. Repository ထဲကို project ဖိုင်အားလုံး upload လုပ်ပြီး commit လုပ်ပါ။ .github folder ကိုပါ upload လုပ်ရပါမယ်။
5. Repository > Actions ကိုဖွင့်ပါ။ GitHub Actions enable လုပ်ရန် မေးလာရင် enable လုပ်ပါ။
6. ဘယ်ဘက် “Build Android APK” ကိုရွေးပြီး “Run workflow” ကိုနှိပ်ပါ။
7. ပြီးသွားရင် workflow run ထဲက Artifacts အောက်ရှိ “DinoHunterWeb-debug-APK” ကို download လုပ်ပါ။
8. ZIP ကိုဖြည်ပြီး app-debug.apk ကို Android ဖုန်းမှာဖွင့် install လုပ်ပါ။ “Install unknown apps” ကို ခွင့်ပြုရနိုင်ပါတယ်။

သတိ: ဒီ APK က debug APK ဖြစ်ပြီး ကိုယ့်ဖုန်းမှာ install/test လုပ်ဖို့ပါ။ Website/game ရဲ့ compatibility နဲ့ save persistence ကို အာမမခံနိုင်ပါ။
