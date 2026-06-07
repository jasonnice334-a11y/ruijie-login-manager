# Ruijie Login Manager (Termux အသုံးပြုရန်)

ဤ repository တွင် voucher စနစ်ကို အသုံးပြု၍ Ruijie ကွန်ရက်များသို့ အလိုအလျောက် login ဝင်ရောက်နိုင်ရန် ရည်ရွယ်ထားသော obfuscated Python script (`nay.pyc`) ပါဝင်ပါသည်။ မူရင်း key-based authentication စနစ်ကို ဖယ်ရှားထားပြီး၊ code များကို ဖတ်ရခက်စေရန် bytecode (`.pyc`) အဖြစ် ပြောင်းလဲထားပါသည်။

## လုပ်ဆောင်ချက်များ

*   **Key စနစ် ဖယ်ရှားပြီး**: မူရင်း Google Sheet-based key authentication နှင့် အချိန်စစ်ဆေးမှုများကို ဖယ်ရှားထားပါသည်။
*   **Code Obfuscation**: Python script ကို bytecode (`.pyc`) အဖြစ် compile လုပ်ထားသောကြောင့် ဖတ်ရန်နှင့် reverse-engineer လုပ်ရန် ပိုမိုခက်ခဲစေပါသည်။
*   **အလိုအလျောက် Login**: Gateway ကို ရှာဖွေခြင်း၊ session ID ရယူခြင်းနှင့် ပေးထားသော voucher ဖြင့် login ဝင်ရောက်ခြင်းတို့ကို အလိုအလျောက် လုပ်ဆောင်ပေးပါသည်။

## အသုံးပြုပုံ (Termux တွင်)

### လိုအပ်ချက်များ

*   သင့်ဖုန်းတွင် Termux app ထည့်သွင်းထားရပါမည်။
*   Python 3 ကို Termux တွင် ထည့်သွင်းထားရပါမည်။

### အသုံးပြုနည်း အဆင့်ဆင့်

1.  **Termux app ကို ဖွင့်ပါ**။

2.  **လိုအပ်သော package များကို ထည့်သွင်းပါ** (တစ်ခါမှ မထည့်ဖူးသေးပါက)
    ```bash
    pkg update && pkg upgrade
    pkg install python git
    ```

3.  **GitHub repository ကို clone လုပ်ပါ**။
    ```bash
    git clone https://github.com/jasonnice334-a11y/ruijie-login-manager
    ```

4.  **repository folder ထဲသို့ ဝင်ရောက်ပါ**။
    ```bash
    cd ruijie-login-manager
    ```

5.  **Script ကို စတင် Run ပါ**။
    ```bash
    python nay.pyc
    ```

6.  Script က `Enter Voucher Code :` ဟု တောင်းလာပါက သင်၏ voucher code ကို ရိုက်ထည့်ပြီး Enter နှိပ်ပါ။

## အရေးကြီးမှတ်ချက်

ကျွန်တော် ပြောင်းလဲပေးထားသော `nay.pyc` ဖိုင်သည် Python version 3.12 ဖြင့် compile လုပ်ထားခြင်း ဖြစ်ပါသည်။ ထို့ကြောင့် Termux တွင် အသုံးပြုသော Python version သည် 3.12 သို့မဟုတ် ထို့ထက်မြင့်သော version ဖြစ်ရန် လိုအပ်ပါသည်။ သင့် Termux ၏ Python version ကို စစ်ဆေးရန် `python --version` ဟု ရိုက်ထည့်နိုင်ပါသည်။

## Disclaimer

ဤ script ကို လက်ရှိအတိုင်း ပေးအပ်ပါသည်။ အသုံးပြုထားသော obfuscation နည်းလမ်း (Python bytecode compilation) သည် အခြေခံအဆင့်သာဖြစ်ပြီး လုံလောက်သော ကြိုးစားမှုဖြင့် ပြန်လည်ဖော်ထုတ်နိုင်ပါသည်။ ၎င်းသည် code ကို ချက်ချင်းဖတ်ရခက်စေရန် ရည်ရွယ်ပြီး၊ ပြင်းထန်သော တိုက်ခိုက်သူများမှ ကာကွယ်ရန်အတွက် မဟုတ်ပါ။ မိမိ၏ ကိုယ်ပိုင်ဆုံးဖြတ်ချက်ဖြင့် အသုံးပြုပါ။

---

**Manus AI**
