# မတူညီသော LLM များကို စူးစမ်းလေ့လာခြင်းနှင့် နှိုင်းယှဉ်ခြင်း

[![မတူညီသော LLM များကို စူးစမ်းလေ့လာခြင်းနှင့် နှိုင်းယှဉ်ခြင်း](./images/02-lesson-banner.png?WT.mc_id=academic-105485-koreyst)](https://aka.ms/gen-ai-lesson2-gh?WT.mc_id=academic-105485-koreyst)

> _ဤသင်ခန်းစာ၏ ဗီဒီယိုကို ကြည့်ရှုရန် အပေါ်ရှိ ပုံကို နှိပ်ပါ_

ယခင်သင်ခန်းစာတွင် Generative AI သည် နည်းပညာနယ်ပယ်ကို မည်သို့ ပြောင်းလဲစေနေသည်၊ Large Language Models (LLMs) များ မည်သို့ အလုပ်လုပ်သည်နှင့် ကျွန်ုပ်တို့၏ startup ကဲ့သို့သော လုပ်ငန်းများက ၎င်းတို့ကို အသုံးချပြီး တိုးတက်အောင်ပြုလုပ်နိုင်သည်ကို တွေ့မြင်ခဲ့ပါသည်။ ဤအခန်းတွင် မတူညီသော Large Language Models (LLMs) များကို နှိုင်းယှဉ်စစ်ဆေးပြီး ၎င်းတို့၏ အားသာချက်များနှင့် အားနည်းချက်များကို နားလည်သဘောပေါက်ရန်ဆက်လက် လေ့လာကြပါမည်။

ကျွန်ုပ်တို့ startup ၏ ခရီးလမ်းတွင် နောက်ထပ်ခြေလှမ်းမှာ LLMs များ၏ လက်ရှိအခြေအနေကို စူးစမ်းလေ့လာပြီး ကျွန်ုပ်တို့၏ အသုံးပြုမှုအတွက် မည်သည်များ သင့်တော်သည်ကို နားလည်ခြင်းဖြစ်သည်။

## နိဒါန်း

ဤသင်ခန်းစာတွင် ပါဝင်မည့်အကြောင်းအရာများ-

- လက်ရှိအခြေအနေတွင် ရှိနေသော မတူညီသော LLM အမျိုးအစားများ။
- Azure တွင် သင့်အသုံးပြုမှုအတွက် မတူညီသော မော်ဒယ်များကို စမ်းသပ်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်းနှင့် နှိုင်းယှဉ်ခြင်း။
- LLM တစ်ခုကို မည်သို့ deploy လုပ်မည်နည်း။

## သင်ယူရရှိမည့် ရည်မှန်းချက်များ

ဤသင်ခန်းစာ ပြီးစီးပြီးနောက် သင်သည်-

- သင့်အသုံးပြုမှုအတွက် သင့်တော်သော မော်ဒယ်ကို ရွေးချယ်နိုင်မည်။
- သင့်မော်ဒယ်၏ စွမ်းဆောင်ရည်ကို စမ်းသပ်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်းနှင့် တိုးတက်စေခြင်း မည်သို့ပြုလုပ်ရမည်ကို နားလည်မည်။
- လုပ်ငန်းများက မော်ဒယ်များကို မည်သို့ deploy လုပ်ကြသည်ကို သိရှိမည်။

## မတူညီသော LLM အမျိုးအစားများကို နားလည်ခြင်း

LLMs များသည် ၎င်းတို့၏ ဗိသုကာ၊ လေ့ကျင့်ရေးဒေတာနှင့် အသုံးပြုမှုအပေါ် အခြေခံ၍ ခွဲခြားမှုများစွာ ရှိနိုင်ပါသည်။ ဤကွဲပြားမှုများကို နားလည်ခြင်းသည် ကျွန်ုပ်တို့၏ startup အတွက် အခြေအနေအလိုက် သင့်တော်သော မော်ဒယ်ကို ရွေးချယ်ရာတွင် အထောက်အကူပြုမည်ဖြစ်ပြီး စွမ်းဆောင်ရည်ကို စမ်းသပ်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်းနှင့် တိုးတက်စေခြင်း မည်သို့ပြုလုပ်ရမည်ကို နားလည်စေမည်ဖြစ်သည်။

LLM မော်ဒယ်အမျိုးအစားများစွာ ရှိပါသည်၊ သင်၏ မော်ဒယ်ရွေးချယ်မှုသည် ၎င်းတို့ကို မည်သည့်အတွက် အသုံးပြုရန် ရည်ရွယ်သည်၊ သင့်ဒေတာ၊ မည်မျှပေးဆောင်ရန် အသင့်ရှိသည်နှင့် အခြားအချက်များပေါ် မူတည်ပါသည်။

စာသား၊ အသံ၊ ဗီဒီယို၊ ပုံဖန်တီးခြင်းနှင့် အခြားအရာများအတွက် မော်ဒယ်များကို အသုံးပြုရန် ရည်ရွယ်သည့်အပေါ် မူတည်၍ မတူညီသော မော်ဒယ်အမျိုးအစားကို ရွေးချယ်နိုင်ပါသည်။

- **အသံနှင့် စကားသံမှတ်ချက်**။ ဤရည်ရွယ်ချက်အတွက် Whisper-type မော်ဒယ်များသည် ခြွေများအသုံးရှိသော ရွေးချယ်မှုတစ်ခုဖြစ်ပြီး ယေဘုယျရည်ရွယ်ချက်အတွက် ဖန်တီးထားကာ စကားသံမှတ်ချက်အတွက် ရည်ရွယ်ထားပါသည်။ မတူညီသော အသံများဖြင့် လေ့ကျင့်ထားပြီး ဘာသာစုံ စကားသံမှတ်ချက်ကို လုပ်ဆောင်နိုင်ပါသည်။ [Whisper type မော်ဒယ်များအကြောင်း နောက်ထပ်သိရှိရန်](https://platform.openai.com/docs/models/whisper?WT.mc_id=academic-105485-koreyst)။

- **ပုံဖန်တီးခြင်း**။ ပုံဖန်တီးခြင်းအတွက် DALL-E နှင့် Midjourney တို့သည် နာမည်ကြီး ရွေးချယ်မှုနှစ်ခုဖြစ်ပါသည်။ DALL-E ကို Azure OpenAI မှ ပံ့ပိုးပေးထားပါသည်။ [DALL-E အကြောင်း နောက်ထပ်ဖတ်ရှုရန်](https://platform.openai.com/docs/models/dall-e?WT.mc_id=academic-105485-koreyst) နှင့်လည်း ဤ curriculum ၏ အခန်း ၉ တွင်လည်း ကြည့်ပါ။

- **စာသားဖန်တီးခြင်း**။ မော်ဒယ်အများစုသည် စာသားဖန်တီးခြင်းအပေါ် လေ့ကျင့်ထားပြီး GPT-3.5 မှ GPT-4 အထိ ရွေးချယ်မှုများစွာ ရှိပါသည်။ ၎င်းတို့သည် မတူညီသော ကုန်ကျစရိတ်များဖြင့် လာပြီး GPT-4 သည် အစကားဆုံးဖြစ်သည်။ စွမ်းဆောင်ရည်နှင့် ကုန်ကျစရိတ်အရ သင့်လိုအပ်ချက်များနှင့် အကောင်းဆုံး ကိုက်ညီသော မော်ဒယ်များကို အကဲဖြတ်ရန် [Azure OpenAI playground](https://oai.azure.com/portal/playground?WT.mc_id=academic-105485-koreyst) ကို ကြည့်ရှုရန် တန်ဖိုးရှိပါသည်။

- **Multi-modality**။ input နှင့် output တွင် မတူညီသော ဒေတာအမျိုးအစားများကို ကိုင်တွယ်လိုပါက [gpt-4 turbo with vision သို့မဟုတ် gpt-4o](https://learn.microsoft.com/azure/ai-services/openai/concepts/models#gpt-4-and-gpt-4-turbo-models?WT.mc_id=academic-105485-koreyst) ကဲ့သို့သော မော်ဒယ်များကို ကြည့်ရှုနိုင်ပါသည် - OpenAI မော်ဒယ်များ၏ နောက်ဆုံး releases များ - ၎င်းတို့သည် သဘာဝ ဘာသာစကား processing နှင့် visual နားလည်မှုကို ပေါင်းစပ်နိုင်ပြီး multi-modal interfaces များမှတဆင့် အပြန်အလှန် တုံ့ဆိုင်မှုများ ပြုလုပ်နိုင်ပါသည်။

မော်ဒယ်တစ်ခုကို ရွေးချယ်ခြင်းဆိုသည်မှာ အခြေခံ စွမ်းရည်အချို့ကို ရရှိခြင်းဖြစ်သော်လည်း၊ ၎င်းမှာ လုံလောက်မည် မဟုတ်ပါ။ မကြာခဏ သင့်တွင် ကုမ္ပဏီ အတွက် သီးသန့် ဒေတာများ ရှိပြီး LLM ကို ထိုအကြောင်းများ အကြောင်းကြားရန် လိုအပ်ပါသည်။ ၎င်းကို မည်သို့ ချဉ်းကပ်ရမည်ဆိုတာအတွက် ရွေးချယ်မှုအမျိုးမျိုး ရှိပါသည်၊ နောက်လာမည့် အပိုင်းများတွင် ပိုမိုရှင်းလင်းပါမည်။

### Foundation Models နှင့် LLMs

Foundation Model ဟူသော အသုံးအနှုန်းကို [Stanford သုတေသီများမှ တီထွင်](https://arxiv.org/abs/2108.07258?WT.mc_id=academic-105485-koreyst) ခဲ့ပြီး အချို့သော စံနှုန်းများကို လိုက်နာသော AI မော်ဒယ်အဖြစ် သတ်မှတ်ပေးထားပါသည်၊ ဥပမာ-

- **၎င်းတို့သည် unsupervised learning သို့မဟုတ် self-supervised learning ကို အသုံးပြု၍ လေ့ကျင့်ထားပါသည်**၊ ဆိုလိုသည်မှာ ၎င်းတို့သည် အမှတ်တံဆိပ်မရှိသော multi-modal ဒေတာများပေါ်တွင် လေ့ကျင့်ထားပြီး ၎င်းတို့၏ လေ့ကျင့်ရေး လုပ်ငန်းစဉ်အတွက် လူသား၏ မှတ်ချက် သို့မဟုတ် အမှတ်တံဆိပ်ခြင်း မလိုအပ်ပါ။
- **၎င်းတို့သည် အလွန်ကြီးမားသော မော်ဒယ်များဖြစ်ပါသည်**၊ ဘီလီယံနှင့်ချီသော parameters များပေါ်တွင် လေ့ကျင့်ထားသော အလွန်နက်ရှိုင်းသော neural networks များပေါ် အခြေခံထားပါသည်။
- **၎င်းတို့သည် ပုံမှန်အားဖြင့် အခြားမော်ဒယ်များအတွက် 'အခြေခံ' အဖြစ် အလုပ်လုပ်ရန် ရည်သည်**၊ ဆိုလိုသည်မှာ ၎င်းတို့သည် fine-tuning အားဖြင့် ပြုလုပ်နိုင်သော အခြားမော်ဒယ်များကို တည်ဆောက်ရန်အတွက် စတင်မှတ်တံဆိပ်အဖြစ် အသုံးပြုနိုင်ပါသည်။

![Foundation Models နှင့် LLMs](./images/FoundationModel.png?WT.mc_id=academic-105485-koreyst)

ပုံရင်းမြစ်: [Essential Guide to Foundation Models and Large Language Models | by Babar M Bhatti | Medium
](https://thebabar.medium.com/essential-guide-to-foundation-models-and-large-language-models-27dab58f7404)

ဤခြားနားချက်ကို နောက်ထပ် ရှင်းလင်းရန်အတွက်၊ ChatGPT ကို ဥပမာအဖြစ် ယူကြည့်ကြပါစို့။ ChatGPT ၏ ပထမ version ကို တည်ဆောက်ရန်အတွက် GPT-3.5 ဟုခေါ်သော မော်ဒယ်သည် foundation model အဖြစ် အလုပ်လုပ်ခဲ့သည်။ ဆိုလိုသည်မှာ OpenAI သည် chat-specific ဒေတာအချို့ကို အသုံးပြု၍ chatbots ကဲ့သို့သော စကားပြောဆိုမှု scenarios များတွင် ကောင်းမွန်စွာ စွမ်းဆောင်ရန် အထူးပြုလုပ်ထားသော GPT-3.5 ၏ tuned version ကို ဖန်တီးခဲ့ခြင်းဖြစ်သည်။

![Foundation Model](./images/Multimodal.png?WT.mc_id=academic-105485-koreyst)

ပုံရင်းမြစ်: [2108.07258.pdf (arxiv.org)](https://arxiv.org/pdf/2108.07258.pdf?WT.mc_id=academic-105485-koreyst)

### Open Source နှင့် Proprietary Models

LLMs များကို ခွဲခြားသည့် နောက်ထပ်နည်းလမ်းတစ်ခုမှာ ၎င်းတို့သည် open source ဖြစ်သည် သို့မဟုတ် proprietary ဖြစ်သည်ဆိုတာပါ။

Open-source မော်ဒယ်များသည် အများပြည်သူအတွက် ရရှိနိုင်စေပြီး မည်သူမဆို အသုံးပြုနိုင်သော မော်ဒယ်များဖြစ်ပါသည်။ ၎င်းတို့သည် မကြာခဏ ၎င်းတို့ကို ဖန်တီးခဲ့သော ကုမ္ပဏီ သို့မဟုတ် သုတေသန community မှ ရရှിနိုင်စေပါသည်။ ဤမော်ဒယ်များသည် LLMs တွင် အမျိုးမျိုးသော အသုံးပြုမှု အကြောင်းများအတွက် စစ်ဆေးခြင်း၊ မွမ်းမံခြင်းနှင့် စိတ်ကြိုက်ပြင်ဆင်ခြင်း ပြုလုပ်ရန် ခွင့်ပြုထားပါသည်။ သို့သော် ၎င်းတို့သည် production အသုံးပြုမှုအတွက် အမြဲတမ်း အကောင်းဆုံး မဟုတ်ပြီး proprietary မော်ဒယ်များကဲ့သို့ စွမ်းဆောင်ရည် မရှိနိုင်ပါ။ ထို့အပြင် open-source မော်ဒယ်များအတွက် ငွေကြေးထောက်ပံ့မှု ကန့်သတ်နိုင်ပြီး ၎င်းတို့သည် ရေရှည် ထိန်းသိမ်းခြင်း မရရှိနိုင် သို့မဟုတ် နောက်ဆုံး သုတေသနများဖြင့် မွမ်းမံခြင်း မရနိုင်ပါ။ လူကြိုက်များသော open source မော်ဒယ်များ၏ ဥပမာများမှာ [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html?WT.mc_id=academic-105485-koreyst)၊ [Bloom](https://huggingface.co/bigscience/bloom) နှင့် [LLaMA](https://llama.meta.com) တို့ဖြစ်ပါသည်။

Proprietary မော်ဒယ်များသည် ကုမ္ပဏီတစ်ခု၏ ပိုင်ဆိုင်မှုဖြစ်ပြီး အများပြည်သူအတွက် ရရှိနိုင်အောင် မလုပ်ပေးထားသော မော်ဒယ်များဖြစ်ပါသည်။ ဤမော်ဒယ်များသည် မကြာခဏ production အသုံးပြုမှုအတွက် အကောင်းဆုံး ပြုလုပ်ထားပါသည်။ သို့သော် ၎င်းတို့သည် စစ်ဆေးခြင်း၊ မွမ်းမံခြင်း သို့မဟုတ် မတူညီသော အသုံးပြုမှုများအတွက် စိတ်ကြိုက်ပြင်ဆင်ခြင်း မပြုလုပ်ရန် ခွင့်မပြုပါ။ ထို့အပြင် ၎င်းတို့သည် အမြဲတမ်း အခမဲ့ မရရှိနိုင်ပြီး အသုံးပြုရန် subscription သို့မဟုတ် payment လိုအပ်နိုင်ပါသည်။ ထို့အပြင် အသုံးပြုသူများသည် မော်ဒယ်ကို လေ့ကျင့်ရန်အတွက် အသုံးပြုသော ဒေတာများကို ထိန်းချုပ်မှု မရရှိသောကြောင့် ဒေတာ ကိုယ်ရေးကိုယ်တာ နှင့် AI ၏ တာဝန်ရှိစွာ အသုံးပြုမှုအတွက် ကတိကဝတ် သေချာစေရန် မော်ဒယ် ပိုင်ရှင်ကို ယုံကြည်ရပါသည်။ လူကြိုក်များသော proprietary မော်ဒယ်များ၏ ဥပမာများမှာ [OpenAI models](https://platform.openai.com/docs/models/overview?WT.mc_id=academic-105485-koreyst)၊ [Google Bard](https://sapling.ai/llm/bard?WT.mc_id=academic-105485-koreyst) သို့မဟုတ် [Claude 2](https://www.anthropic.com/index/claude-2?WT.mc_id=academic-105485-koreyst) တို့ဖြစ်ပါသည်။

### Embedding နှင့် Image generation နှင့် Text and Code generation

LLMs များကို ၎င်းတို့ ထုတ်ပေးသော output အားဖြင့်လည်း ခွဲခြားနိုင်ပါသည်။

Embeddings များသည် စာသားကို embedding ဟုခေါ်သော ကိန်းဂဏန်းပုံစံအဖြစ် ပြောင်းလဲနိုင်သော မော်ဒယ်အစုံတစ်ခုဖြစ်ပြီး၊ ၎င်းသည် input စာသား၏ ကိန်းဂဏန်း ကိုယ်စားပြုမှုဖြစ်သည်။ Embeddings များသည် စက်များအတွက် စကားလုံးများ သို့မဟုတ် စာကြောင်းများအကြား ဆက်နွယ်မှုများကို နားလည်ရန် ပိုမိုလွယ်ကူစေပြီး ကိန်းဂဏန်း ဒေတာများပေါ်တွင် ပိုမိုကောင်းမွန်သော စွမ်းဆောင်ရည်ရှိသော classification မော်ဒယ်များ သို့မဟုတ် clustering မော်ဒယ်များကဲ့သို့သော အခြားမော်ဒယ်များ၏ inputs များအဖြစ် အသုံးပြုနိုင်ပါသည်။ Embedding မော်ဒယ်များကို မကြာခဏ transfer learning အတွက် အသုံးပြုပြီး၊ ဒေတာ ပြည့်စုံမှု ရှိသော surrogate task တစ်ခုအတွက် မော်ဒယ်တစ်ခု တည်ဆောက်ပြီး နောက်ပိုင်းတွင် မော်ဒယ် weights (embeddings) များကို အခြား downstream tasks များအတွက် ပြန်လည်အသုံးပြုပါသည်။ ဤအမျိုးအစား၏ ဥပမာမှာ [OpenAI embeddings](https://platform.openai.com/docs/models/embeddings?WT.mc_id=academic-105485-koreyst) ဖြစ်သည်။

![Embedding](./images/Embedding.png?WT.mc_id=academic-105485-koreyst)

ပုံရိပ်ထုတ်လုပ်ခြင်း မော်ဒယ်များသည် ပုံရိပ်များကို ထုတ်လုပ်သည့် မော်ဒယ်များဖြစ်သည်။ ဤမော်ဒယ်များကို ပုံရိပ်တည်းဖြတ်ခြင်း၊ ပုံရိပ်ပေါင်းစပ်ခြင်း၊ နှင့် ပုံရိပ်ဘာသာပြန်ခြင်းများအတွက် မကြာခဏ အသုံးပြုကြသည်။ ပုံရိပ်ထုတ်လုပ်ခြင်း မော်ဒယ်များကို [LAION-5B](https://laion.ai/blog/laion-5b/?WT.mc_id=academic-105485-koreyst) ကဲ့သို့သော ပုံရိပ်အချက်အလက်များ၏ ကြီးမားသော dataset များဖြင့် training ပေးလေ့ရှိပြီး၊ ပုံရိပ်အသစ်များ ထုတ်လုပ်ရန် သို့မဟုတ် ရှိပြီးသား ပုံရိပ်များကို inpainting၊ super-resolution၊ နှင့် colorization နည်းပညာများဖြင့် တည်းဖြတ်ရန် အသုံးပြုနိုင်သည်။ ဥပမာများမှာ [DALL-E-3](https://openai.com/dall-e-3?WT.mc_id=academic-105485-koreyst) နှင့် [Stable Diffusion models](https://github.com/Stability-AI/StableDiffusion?WT.mc_id=academic-105485-koreyst) တို့ ပါဝင်သည်။

![Image generation](./images/Image.png?WT.mc_id=academic-105485-koreyst)

စာသားနှင့် code ထုတ်လုပ်ခြင်း မော်ဒယ်များသည် စာသား သို့မဟုတ် code များကို ထုတ်လုပ်သည့် မော်ဒယ်များဖြစ်သည်။ ဤမော်ဒယ်များကို စာသား အကျဉ်းချုပ်ခြင်း၊ ဘာသာပြန်ခြင်း၊ နှင့် မေးခွန်းဖြေဆိုခြင်းများအတွက် မကြာခဏ အသုံးပြုကြသည်။ စာသားထုတ်လုပ်ခြင်း မော်ဒယ်များကို [BookCorpus](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zhu_Aligning_Books_and_ICCV_2015_paper.html?WT.mc_id=academic-105485-koreyst) ကဲ့သို့သော စာသားများ၏ ကြီးမားသော dataset များဖြင့် training ပေးလေ့ရှိပြီး၊ စာသားအသစ်များ ထုတ်လုပ်ရန် သို့မဟုတ် မေးခွန်းများကို ဖြေဆိုရန် အသုံးပြုနိုင်သည်။ [CodeParrot](https://huggingface.co/codeparrot?WT.mc_id=academic-105485-koreyst) ကဲ့သို့သော Code ထုတ်လုပ်ခြင်း မော်ဒယ်များကို GitHub ကဲ့သို့သော code များ၏ ကြီးမားသော dataset များဖြင့် training ပေးလေ့ရှိပြီး၊ code အသစ်များ ထုတ်လုပ်ရန် သို့မဟုတ် ရှိပြီးသား code များရှိ bug များကို ပြင်ဆင်ရန် အသုံးပြုနိုင်သည်။

![Text and code generation](./images/Text.png?WT.mc_id=academic-105485-koreyst)

### Encoder-Decoder နှင့် Decoder-only

LLM များ၏ architecture အမျိုးအစားများအကြောင်း ပြောရန်အတွက် ဥပမာတစ်ခုကို အသုံးပြုကြပါစို့။

သင့်မန်နေဂျာက ကျောင်းသားများအတွက် စာမေးပွဲတစ်စောင် ရေးရန် အလုပ်တစ်ခု ပေးခဲ့သည်ဟု စိတ်ကူးကြည့်ပါ။ သင့်မှာ လုပ်ဖော်ကိုင်ဖက် နှစ်ယောက်ရှိသည်၊ တစ်ယောက်က အကြောင်းအရာ ဖန်တီးခြင်းကို တာဝန်ယူပြီး အခြားတစ်ယောက်က ၎င်းတို့ကို ပြန်လည်သုံးသပ်ခြင်းကို တာဝန်ယူသည်။

အကြောင်းအရာ ဖန်တီးသူသည် Decoder only model ကဲ့သို့ဖြစ်သည်၊ သူတို့သည် အကြောင်းအရာကို ကြည့်နိုင်ပြီး သင်ရေးပြီးသား အရာများကို မြင်ပြီးနောက် ၎င်းအပေါ်အခြေခံ၍ သင်ခန်းစာတစ်ခု ရေးနိုင်သည်။ သူတို့သည် စွဲမက်ဖွယ်နှင့် အသိပညာရှိသော အကြောင်းအရာများ ရေးရန် အလွန်ကောင်းသော်လည်း အကြောင်းအရာနှင့် သင်ယူမှု ရည်မှန်းချက်များကို နားလည်ရန်မှာ မကောင်းပါ။ Decoder model များ၏ ဥပမာများမှာ GPT-3 ကဲ့သို့သော GPT မိသားစု မော်ဒယ်များ ဖြစ်သည်။

ပြန်လည်သုံးသပ်သူသည် Encoder only model ကဲ့သို့ဖြစ်သည်၊ သူတို့သည် ရေးထားသော သင်ခန်းစာနှင့် အဖြေများကို ကြည့်ပြီး ၎င်းတို့အကြား ဆက်စပ်မှုကို သတိပြုမိကာ context ကို နားလည်သော်လည်း အကြောင်းအရာ ထုတ်လုပ်ရန်မှာ မကောင်းပါ။ Encoder only model ၏ ဥပမာမှာ BERT ဖြစ်သည်။

စာမေးပွဲကို ဖန်တီးပြီး ပြန်လည်သုံးသပ်နိုင်သူတစ်ယောက်လည်း ရှိနိုင်သည်ဟု စိတ်ကူးကြည့်ပါ၊ ဤအရာသည် Encoder-Decoder model ဖြစ်သည်။ ဥပမာများမှာ BART နှင့် T5 တို့ ဖြစ်သည်။

### Service နှင့် Model

ယခုပင် service နှင့် model အကြား ခြားနားချက်အကြောင်း ပြောကြပါစို့။ Service တစ်ခုသည် Cloud Service Provider မှ ပေးအပ်သော ထုတ်ကုန်တစ်ခုဖြစ်ပြီး မကြာခဏ မော်ဒယ်များ၊ အချက်အလက်များ၊ နှင့် အခြား အစိတ်အပိုင်းများ၏ ပေါင်းစပ်မှုဖြစ်သည်။ Model တစ်ခုသည် service ၏ အဓိက အစိတ်အပိုင်းဖြစ်ပြီး မကြာခဏ LLM ကဲ့သို့သော foundation model တစ်ခု ဖြစ်သည်။

Service များကို production အသုံးပြုမှုအတွက် optimized လုပ်ထားလေ့ရှိပြီး မော်ဒယ်များထက် အသုံးပြုရန် ပိုမိုလွယ်ကူလေ့ရှိသည်၊ graphical user interface မှတစ်ဆင့်ဖြစ်သည်။ သို့သော် service များသည် အမြဲတမ်း အခမဲ့ မရရှိနိုင်ပါ၊ နှင့် အသုံးပြုရန်အတွက် subscription သို့မဟုတ် ငွေပေးချေမှု လိုအပ်နိုင်သည်၊ service ပိုင်ရှင်၏ စက်ပစ္စည်းများနှင့် resources များကို အသုံးပြုခြင်း၊ ကုန်ကျစရိတ်များကို optimize လုပ်ခြင်း နှင့် လွယ်ကူစွာ scaling လုပ်ခြင်းတို့နှင့် လဲလှယ်၍ဖြစ်သည်။ Service ၏ ဥပမာမှာ [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/overview?WT.mc_id=academic-105485-koreyst) ဖြစ်ပြီး၊ pay-as-you-go rate plan ကို ပေးအပ်သည်၊ ဆိုလိုသည်မှာ အသုံးပြုသူများကို ၎င်းတို့က service ကို မည်မျှအသုံးပြုသည်နှင့် အချိုးကျ တောင်းခံခြင်းဖြစ်သည်။ ထို့အပြင် Azure OpenAI Service သည် မော်ဒယ်များ၏ စွမ်းရည်များအပေါ် enterprise-grade လုံခြုံရေးနှင့် တာဝန်ရှိသော AI framework ကို ပေးဆောင်သည်။

Model များသည် parameters၊ weights၊ နှင့် အခြားအရာများပါသော Neural Network သာလျှင် ဖြစ်သည်။ ကုမ္ပဏီများအား locally လုပ်ဆောင်ခွင့်ပြုသော်လည်း စက်ပစ္စည်းများ ဝယ်ယူရန်၊ scaling လုပ်ရန်အတွက် အဆောက်အအုံတစ်ခု တည်ဆောက်ရန် နှင့် license ဝယ်ယူရန် သို့မဟုတ် open-source model တစ်ခု အသုံးပြုရန် လိုအပ်လိမ့်မည်။ LLaMA ကဲ့သို့သော model တစ်ခုကို အသုံးပြုရန် ရရှိနိုင်ပြီး၊ မော်ဒယ်ကို လုပ်ဆောင်ရန်အတွက် computational power လိုအပ်သည်။

## Azure တွင် performance ကို နားလည်ရန်အတွက် မတူညီသော မော်ဒယ်များဖြင့် စမ်းသပ်ပြီး ထပ်ခါထပ်ခါ လုပ်ဆောင်နည်း

ကျွန်ုပ်တို့၏ အဖွဲ့သည် လက်ရှိ LLM များ၏ landscape ကို စူးစမ်းပြီး ၎င်းတို့၏ scenarios များအတွက် ကောင်းသော အလားအလာရှိသူများကို ခွဲခြားသတ်မှတ်ပြီးနောက်၊ နောက်ထပ် အဆင့်မှာ ၎င်းတို့ကို ၎င်းတို့၏ ဒေတာပေါ်တွင်နှင့် ၎င်းတို့၏ workload ပေါ်တွင် စမ်းသပ်ခြင်း ဖြစ်သည်။ ဤသည်မှာ ထပ်ခါထပ်ခါ လုပ်ဆောင်သော လုပ်ငန်းစဉ်တစ်ခုဖြစ်ပြီး စမ်းသပ်မှုများနှင့် တိုင်းတာမှုများဖြင့် လုပ်ဆောင်သည်။
ယခင် အပိုဒ်များတွင် ကျွန်ုပ်တို့ ဖော်ပြခဲ့သော မော်ဒယ်အများစု (OpenAI မော်ဒယ်များ၊ Llama2 ကဲ့သို့သော open source မော်ဒယ်များ၊ နှင့် Hugging Face transformers) သည် [Azure AI Studio](https://ai.azure.com/?WT.mc_id=academic-105485-koreyst) ရှိ [Model Catalog](https://learn.microsoft.com/azure/ai-studio/how-to/model-catalog-overview?WT.mc_id=academic-105485-koreyst) တွင် ရရှိနိုင်သည်။

[Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/what-is-ai-studio?WT.mc_id=academic-105485-koreyst) သည် developer များအတွက် generative AI applications များ တည်ဆောက်ရန်နှင့် စမ်းသပ်မှုမှ အကဲဖြတ်မှုအထိ - တစ်ခုလုံး development lifecycle ကို စီမံခန့်ခွဲရန် ဒီဇိုင်းထုတ်ထားသော Cloud Platform တစ်ခုဖြစ်ပြီး၊ Azure AI services အားလုံးကို hub တစ်ခုအဖြစ် ပေါင်းစပ်ထားပြီး အသုံးပြုရလွယ်ကူသော GUI ပါရှိသည်။ Azure AI Studio ရှိ Model Catalog သည် အသုံးပြုသူအား အောက်ပါအရာများကို လုပ်ဆောင်နိုင်စေသည်-

- Catalog တွင် စိတ်ဝင်စားသော Foundation Model ကို ရှာဖွေခြင်း - proprietary သို့မဟုတ် open source နှစ်မျိုးလုံး၊ task၊ license၊ သို့မဟုတ် နာမည်အရ filter လုပ်ခြင်း။ ရှာဖွေမှုကို တိုးတက်စေရန်အတွက်၊ မော်ဒယ်များကို Azure OpenAI collection၊ Hugging Face collection၊ နှင့် အခြားများကဲ့သို့သော collection များအဖြစ် စုစည်းထားသည်။

![Model catalog](./images/AzureAIStudioModelCatalog.png?WT.mc_id=academic-105485-koreyst)

- အသုံးပြုရန် ရည်ရွယ်ချက်နှင့် training data များ၊ code နမူနာများ နှင့် internal evaluations library ပေါ်တွင် အကဲဖြတ်မှု ရလဒ်များ အပါအဝင် အသေးစိတ် ဖော်ပြချက်ပါသော model card ကို ပြန်လည်သုံးသပ်ခြင်း။

![Model card](./images/ModelCard.png?WT.mc_id=academic-105485-koreyst)

- [Model Benchmarks](https://learn.microsoft.com/azure/ai-studio/how-to/model-benchmarks?WT.mc_id=academic-105485-koreyst) pane မှတစ်ဆင့် industry တွင် ရရှိနိုင်သော မော်ဒယ်များနှင့် dataset များ အကြား benchmark များကို နှိုင်းယှဉ်ပြီး မည်သည့်အရာက business scenario နှင့် ကိုက်ညီသည်ကို အကဲဖြတ်ခြင်း။

![Model benchmarks](./images/ModelBenchmarks.png?WT.mc_id=academic-105485-koreyst)

- Azure AI Studio ၏ စမ်းသပ်မှုနှင့် ခြေရာခံမှု စွမးရည်များကို အသုံးချ၍ တိကျသော workload တစ်ခုတွင် မော်ဒယ် performance ကို တိုးတက်စေရန်အတွက် custom training data ပေါ်တွင် မော်ဒယ်ကို Fine-tune လုပ်ခြင်း။

![Model fine-tuning](./images/FineTuning.png?WT.mc_id=academic-105485-koreyst)

- Applications များက စားသုံးနိုင်စေရန်အတွက် မူလ pre-trained model သို့မဟုတ် fine-tuned version ကို remote real time inference - managed compute - သို့မဟုတ် serverless api endpoint - [pay-as-you-go](https://learn.microsoft.com/azure/ai-studio/how-to/model-catalog-overview#model-deployment-managed-compute-and-serverless-api-pay-as-you-go?WT.mc_id=academic-105485-koreyst) - သို့ deploy လုပ်ခြင်း။

![Model deployment](./images/ModelDeploy.png?WT.mc_id=academic-105485-koreyst)

> [!NOTE]
> Catalog ရှိ မော်ဒယ်အားလုံးသည် လောလောဆယ် fine-tuning နှင့်/သို့မဟုတ် pay-as-you-go deployment အတွက် ရရှိနိုင်သည် မဟုတ်ပါ။ မော်ဒယ်၏ စွမးရည်များနှင့် ကန့်သတ်ချက်များအကြောင်း အသေးစိတ်သိရန် model card ကို စစ်ဆေးပါ။

## LLM ရလဒ်များကို တိုးတက်စေခြင်း

ကျွန်ုပ်တို့သည် ကျွန်ုပ်တို့၏ startup အဖွဲ့နှင့်အတူ LLM အမျိုးအစားများ မတူညီကြောင်းနှင့် Cloud Platform (Azure Machine Learning) တစ်ခုကို စူစမ်းပြီးနောက်၊ ကျွန်ုပ်တို့အား မတူညီသော မော်ဒယ်များကို နှိုင်းယှဉ်ရန်၊ test data ပေါ်တွင် ၎င်းတို့ကို အကဲဖြတ်ရန်၊ performance ကို တိုးတက်စေရန် နှင့် ၎င်းတို့ကို inference endpoints များပေါ်တွင် deploy လုပ်ရန် ခွင့်ပြုထားသည်။

သို့သော် ၎င်းတို့သည် pre-trained တစ်ခုကို အသုံးပြုခြင်းထက် မော်ဒယ်တစ်ခုကို fine-tuning လုပ်ခြင်းကို မည်သည့်အချိန်တွင် စဉ်းစားသင့်သနည်း။ တိကျသော workload များတွင် မော်ဒယ် performance ကို တိုးတက်စေရန်အတွက် အခြား approach များ ရှိသလား။

LLM တစ်ခုမှ လိုအပ်သော ရလဒ်များ ရရှိရန်အတွက် လုပ်ငန်းတစ်ခုက အသုံးပြုနိုင်သော approach များစွာ ရှိသည်။ Production တွင် LLM တစ်ခုကို deploy လုပ်သည့်အခါ မတူညီသော degree များရှိသော training ဖြင့် မတူညီသော မော်ဒယ်အမျိုးအစားများကို ရွေးချယ်နိုင်သည်၊ complexity၊ cost၊ နှင့် quality အဆင့်အမျိုးမျိုးနှင့်အတူ။ ဤသည်မှာ မတူညီသော approach များ ဖြစ်သည်-

- **Context ပါသော Prompt engineering**။ အယူအဆမှာ လိုအပ်သော response များ ရရှိကြောင်း သေချာစေရန်အတွက် prompt လုပ်သည့်အခါ လုံလောက်သော context ကို ပေးအပ်ခြင်း ဖြစ်သည်။

- **Retrieval Augmented Generation, RAG**။ သင့်ဒေတာသည် database သို့မဟုတ် web endpoint တွင် ရှိနိုင်သည်၊ ဥပမာအားဖြင့်၊ ဤဒေတာ သို့မဟုတ် ၎င်း၏ အစိတ်အပိုင်းတစ်ခုကို prompting အချိန်တွင် ပါဝင်ကြောင်း သေချာစေရန်အတွက်၊ သင်သည် သက်ဆိုင်သော ဒေတာကို ယူဆောင်နိုင်ပြီး ၎င်းကို အသုံးပြုသူ၏ prompt ၏ အစိတ်အပိုင်းတစ်ခု ဖြစ်စေနိုင်သည်။

- **Fine-tuned model**။ ဤနေရာတွင်၊ သင်သည် သင့်ကိုယ်ပိုင် ဒေတာပေါ်တွင် မော်ဒယ်ကို ထပ်မံ training ပေးခဲ့ပြီး မော်ဒယ်သည် သင့်လိုအပ်ချက်များအတွက် ပိုမို တိကျပြီး responsive ဖြစ်လာသော်လည်း ကုန်ကျစရိတ် များနိုင်သည်။

![LLMs deployment](./images/Deploy.png?WT.mc_id=academic-105485-koreyst)

Img source: [Four Ways that Enterprises Deploy LLMs | Fiddler AI Blog](https://www.fiddler.ai/blog/four-ways-that-enterprises-deploy-llms?WT.mc_id=academic-105485-koreyst)

### Context ပါသော Prompt Engineering

Pre-trained LLM များသည် generalized natural language task များတွင် အလွန်ကောင်းမွန်စွာ လုပ်ဆောင်သည်၊ စာကြောင်းတစ်ကြောင်း ပြီးမြောက်စေရန် သို့မဟုတ် မေးခွန်းတစ်ခုကဲ့သို့သော prompt တိုတစ်ခုဖြင့် ၎င်းတို့ကို ခေါ်ခြင်းဖြင့်ပင် - "zero-shot" learning ဟုခေါ်သော်လည်း ဖြစ်သည်။

သို့သော် အသုံးပြုသူသည် ၎င်းတို့၏ query ကို ပိုမိုကောင်းစွာ ဖော်ပြနိုင်သည်နှင့်အမျှ၊ အသေးစိတ် တောင်းဆိုမှုနှင့် ဥပမာများ - Context - ပါသော်လည်း၊ အဖြေသည် ပိုမို တိကျပြီး အသုံးပြုသူ၏ မျှော်လင့်ချက်များနှင့် ပိုမို နီးကပ်လာမည်ဖြစ်သည်။ ဤကိစ္စတွင်၊ prompt တွင် ဥပမာတစ်ခုသာ ပါဝင်လျှင် "one-shot" learning နှင့် ဥပမာများစွာ ပါဝင်လျှင် "few shot learning" ဟု ပြောကြသည်။
Context ပါသော Prompt engineering သည် စတင်လုပ်ဆောင်ရန်အတွက် စရိတ်သက်သာဆုံး approach ဖြစ်သည်။

### Retrieval Augmented Generation (RAG)

LLM များတွင် ၎င်းတို့၏ training လုပ်ငန်းစဉ်အတွင်း အသုံးပြုခဲ့သော ဒေတာကိုသာ အဖြေထုတ်လုပ်ရန်အတွက် အသုံးပြုနိုင်သည်ဟူသော ကန့်သတ်ချက် ရှိသည်။ ဆိုလိုသည်မှာ ၎င်းတို့၏ training လုပ်ငန်းစဉ်ပြီးနောက် ဖြစ်ပျက်ခဲ့သော အချက်အလက်များအကြောင်း မည်သည့်အရာမှ မသိသကဲ့သို့၊ public မဟုတ်သော အချက်အလက်များ (ကုမ္ပဏီဒေတာကဲ့သို့) ကိုလည်း အသုံးပြုနိုင်မည် မဟုတ်ပါ။

ဤအရာကို RAG မှတဆင့် ကျော်လွှားနိုင်သည်၊ prompt length ကန့်သတ်ချက်များကို ထည့်သွင်းစဉ်းစားပြီး documents များ၏ chunks များ ပုံစံဖြင့် external data ဖြင့် prompt ကို တိုးချဲ့သော နည်းပညာတစ်ခုဖြစ်သည်။ ဤအရာကို မတူညီသော ကြိုတင်သတ်မှတ်ထားသော data sources များမှ အသုံးဝင်သော chunks များကို ရယူပြီး ၎င်းတို့ကို prompt Context တွင် ထည့်သွင်းသည့် ([Azure Vector Search](https://learn.microsoft.com/azure/search/vector-search-overview?WT.mc_id=academic-105485-koreyst) ကဲ့သို့သော) Vector database tools များက ပံ့ပိုးထားသည်။

ဤနည်းပညာသည် လုပ်ငန်းတစ်ခုတွင် LLM တစ်ခုကို fine-tune လုပ်ရန်အတွက် လုံလောက်သော ဒေတာ၊ လုံလောက်သော အချိန်၊ သို့မဟုတ် resources မရှိသော်လည်း တိကျသော workload တစ်ခုတွင် performance ကို တိုးတက်စေရန် နှင့ fabrications များ၏ အန္တရာယ်များကို လျှော့ချရန် - ဆိုလိုသည်မှာ အမှန်တရားကို ရှုပ်ထွေးစေခြင်း သို့မဟုတ် အန္တရာယ်ရှိသော အကြောင်းအရာများ - ကို လိုလားနေသောအခါ အလွန်အသုံးဝင်သည်။

### Fine-tuned model

Fine-tuning သည် downstream task တစ်ခုနှင့် 'လိုက်လျောညီထွေ' ဖြစ်စေရန် သို့မဟုတ် တိကျသော ပြဿနာတစ်ခုကို ဖြေရှင်းရန်အတွက် မော်ဒယ်ကို transfer learning ကို အသုံးချသော လုပ်ငန်းစဉ်တစ်ခုဖြစ်သည်။ Few-shot learning နှင့် RAG တို့နှင့် မတူညီစွာ၊ ၎င်းသည် အသစ်သော မော်ဒယ်တစ်ခု ထုတ်လုပ်ခြင်းကို ဖြစ်ပေါ်စေပြီး weights နှင့် biases များကို update လုပ်ထားသည်။ ၎င်းသည် input တစ်ခု (prompt) နှင့် ၎င်းနှင့် ဆက်စပ်သော output (completion) ပါဝင်သော training examples အစုတစ်ခု လိုအပ်သည်။

ဤသည်မှာ အောက်ပါအခြေအနေများတွင် ပိုမို နှစ်သက်ဖွယ် approach ဖြစ်လိမ့်မည်-

- **Fine-tuned models များ အသုံးပြုခြင်း**။ လုပ်ငန်းတစ်ခုသည် high performance models များထက် fine-tuned လုပ်ထားသော စွမ်းရည်နည်းသော models များ (embedding models ကဲ့သို့) ကို အသုံးပြုလိုသည်၊ ပိုမို cost effective နှင့် မြန်ဆန်သော ဖြေရှင်းချက်ကို ရရှိစေသည်။

- **Latency ကို စဉ်းစားခြင်း**။ တိကျသော use-case တစ်ခုအတွက် Latency က အရေးကြီးသောကြောင့် အလွန်ရှည်သော prompts များကို အသုံးပြုရန် မဖြစ်နိုင်သည် သို့မဟုတ် မော်ဒယ်မှ လေ့လာရမည့် ဥပမာများ၏ အရေအတွက်က prompt length limit နှင့် မကိုက်ညီပါ။

- **နောက်ဆုံးပေါ် အချက်အလက်များ ထိန်းသိမ်းခြင်း**။ လုပ်ငန်းတစ်ခုတွင် အရည်အသွေးမြင့် ဒေတာများစွာနှင့် ground truth labels များ ရှိပြီး အချိန်နှင့်အမျှ ဤဒေတာကို နောက်ဆုံးပေါ် ထိန်းသိမ်းရန် လိုအပ်သော resources များ ရှိသည်။

### Trained model

LLM တစ်ခုကို အစမှ training ပေးခြင်းသည် လက်ခံရန် အခက်ခဲဆုံးနှင့် အရှုပ်ထွေးဆုံး approach ဖြစ်သည်မှာ သေချာပါသည်၊ အမြောက်အမြားသော ဒေတာများ၊ ကျွမ်းကျင်သော resources များ၊ နှင့် သင့်လျော်သော computational power များ လိုအပ်သည်။ ဤရွေးချယ်မှုကို လုပ်ငန်းတစ်ခုတွင် domain-specific use case တစ်ခုနှင့် domain-centric ဒေတာများ အမြောက်အမြား ရှိသည့် scenario တစ်ခုတွင်သာ စဉ်းစားသင့်သည်။

## Knowledge check

LLM completion ရလဒ်များကို တိုးတက်စေရန်အတွက် ကောင်းသော approach တစ်ခု ဘာဖြစ်နိုင်မလဲ။

1. Context ပါသော Prompt engineering
1. RAG
1. Fine-tuned model

A:3, သင့်တွင် အချိန်နှင့် resources များနှင့် အရည်အသွေးမြင့် ဒေတာများ ရှိလျှင်၊ fine-tuning သည် နောက်ဆုံးပေါ် အချက်အလက်များ ထိန်းသိမ်းရန်အတွက် ပိုမိုကောင်းသော ရွေးချယ်မှု ဖြစ်သည်။ သို့သော် သင်သည် အရာများကို တိုးတက်စေရန် ကြိုးစားနေပြီး အချိန်မရှိလျှင် RAG ကို ဦးစွာ စဉ်းစားရန် တန်ဖိုးရှိသည်။

## 🚀 Challenge

သင့်လုပ်ငန်းအတွက် [RAG ကို မည်သို့ အသုံးပြုနိုင်မည်](https://learn.microsoft.com/azure/search/retrieval-augmented-generation-overview?WT.mc_id=academic-105485-koreyst) ကို ပိုမို လေ့လာကြည့်ပါ။

## အလွန်ကောင်းပါသည်၊ သင့်သင်ယူမှုကို ဆက်လက်လုပ်ဆောင်ပါ

ဤသင်ခန်းစာကို ပြီးမြောက်ပြီးနောက်၊ သင့် Generative AI အသိပညာကို ဆက်လက် တိုးတက်စေရန်အတွက် ကျွန်ုပ်တို့၏ [Generative AI Learning collection](https://aka.ms/genai-collection?WT.mc_id=academic-105485-koreyst) ကို ကြည့်ရှုပါ!

Lesson 3 သို့ ဦးတည်ပါ၊ ဤနေရာတွင် ကျွန်ုပ်တို့သည် [Generative AI နှင့် တာဝန်ရှိစွာ တည်ဆောက်နည်း](../03-using-generative-ai-responsibly/README.md?WT.mc_id=academic-105485-koreyst) ကို လေ့လာမည်ဖြစ်သည်!

# Exploring and comparing different LLMs

[![Exploring and comparing different LLMs](./images/02-lesson-banner.png?WT.mc_id=academic-105485-koreyst)](https://aka.ms/gen-ai-lesson2-gh?WT.mc_id=academic-105485-koreyst)

> _Click the image above to view video of this lesson_

With the previous lesson, we have seen how Generative AI is changing the technology landscape, how Large Language Models (LLMs) work and how a business - like our startup - can apply them to their use cases and grow! In this chapter, we're looking to compare and contrast different types of large language models (LLMs) to understand their pros and cons.

The next step in our startup's journey is exploring the current landscape of LLMs and understanding which are suitable for our use case.

## Introduction

This lesson will cover:

- Different types of LLMs in the current landscape.
- Testing, iterating, and comparing different models for your use case in Azure.
- How to deploy an LLM.

## Learning Goals

After completing this lesson, you will be able to:

- Select the right model for your use case.
- Understand how to test, iterate, and improve the performance of your model.
- Know how businesses deploy models.

## Understand different types of LLMs

LLMs can have multiple categorizations based on their architecture, training data, and use case. Understanding these differences will help our startup select the right model for the scenario, and understand how to test, iterate, and improve performance.

There are many different types of LLM models, your choice of model depends on what you aim to use them for, your data, how much you're ready to pay and more.

Depending on if you aim to use the models for text, audio, video, image generation and so on, you might opt for a different type of model.

- **Audio and speech recognition**. For this purpose, Whisper-type models are a great choice as they're general-purpose and aimed at speech recognition. It's trained on diverse audio and can perform multilingual speech recognition. Learn more about [Whisper type models here](https://platform.openai.com/docs/models/whisper?WT.mc_id=academic-105485-koreyst).

- **Image generation**. For image generation, DALL-E and Midjourney are two very well-known choices. DALL-E is offered by Azure OpenAI. [Read more about DALL-E here](https://platform.openai.com/docs/models/dall-e?WT.mc_id=academic-105485-koreyst) and also in Chapter 9 of this curriculum.

- **Text generation**. Most models are trained on text generation and you have a large variety of choices from GPT-3.5 to GPT-4. They come at different costs with GPT-4 being the most expensive. It's worth looking into the [Azure OpenAI playground](https://oai.azure.com/portal/playground?WT.mc_id=academic-105485-koreyst) to evaluate which models best fit your needs in terms of capability and cost.

- **Multi-modality**. If you're looking to handle multiple types of data in input and output, you might want to look into models like [gpt-4 turbo with vision or gpt-4o](https://learn.microsoft.com/azure/ai-services/openai/concepts/models#gpt-4-and-gpt-4-turbo-models?WT.mc_id=academic-105485-koreyst) - the latest releases of OpenAI models - which are capable to combine natural language processing to visual understanding, enabling interactions through multi-modal interfaces.

Selecting a model means you get some basic capabilities, that might not be enough however. Often you have company specific data that you somehow need to tell the LLM about. There are a few different choices on how to approach that, more on that in the upcoming sections.

### Foundation Models versus LLMs

The term Foundation Model was [coined by Stanford researchers](https://arxiv.org/abs/2108.07258?WT.mc_id=academic-105485-koreyst) and defined as an AI model that follows some criteria, such as:

- **They are trained using unsupervised learning or self-supervised learning**, meaning they are trained on unlabeled multi-modal data, and they do not require human annotation or labeling of data for their training process.
- **They are very large models**, based on very deep neural networks trained on billions of parameters.
- **They are normally intended to serve as a ‘foundation’ for other models**, meaning they can be used as a starting point for other models to be built on top of, which can be done by fine-tuning.

![Foundation Models versus LLMs](./images/FoundationModel.png?WT.mc_id=academic-105485-koreyst)

Image source: [Essential Guide to Foundation Models and Large Language Models | by Babar M Bhatti | Medium
](https://thebabar.medium.com/essential-guide-to-foundation-models-and-large-language-models-27dab58f7404)

To further clarify this distinction, let’s take ChatGPT as an example. To build the first version of ChatGPT, a model called GPT-3.5 served as the foundation model. This means that OpenAI used some chat-specific data to create a tuned version of GPT-3.5 that was specialized in performing well in conversational scenarios, such as chatbots.

![Foundation Model](./images/Multimodal.png?WT.mc_id=academic-105485-koreyst)

Image source: [2108.07258.pdf (arxiv.org)](https://arxiv.org/pdf/2108.07258.pdf?WT.mc_id=academic-105485-koreyst)

### Open Source versus Proprietary Models

Another way to categorize LLMs is whether they are open source or proprietary.

Open-source models are models that are made available to the public and can be used by anyone. They are often made available by the company that created them, or by the research community. These models are allowed to be inspected, modified, and customized for the various use cases in LLMs. However, they are not always optimized for production use, and may not be as performant as proprietary models. Plus, funding for open-source models can be limited, and they may not be maintained long term or may not be updated with the latest research. Examples of popular open source models include [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html?WT.mc_id=academic-105485-koreyst), [Bloom](https://huggingface.co/bigscience/bloom) and [LLaMA](https://llama.meta.com).

Proprietary models are models that are owned by a company and are not made available to the public. These models are often optimized for production use. However, they are not allowed to be inspected, modified, or customized for different use cases. Plus, they are not always available for free, and may require a subscription or payment to use. Also, users do not have control over the data that is used to train the model, which means they should entrust the model owner with ensuring commitment to data privacy and responsible use of AI. Examples of popular proprietary models include [OpenAI models](https://platform.openai.com/docs/models/overview?WT.mc_id=academic-105485-koreyst), [Google Bard](https://sapling.ai/llm/bard?WT.mc_id=academic-105485-koreyst) or [Claude 2](https://www.anthropic.com/index/claude-2?WT.mc_id=academic-105485-koreyst).

### Embedding versus Image generation versus Text and Code generation

LLMs can also be categorized by the output they generate.

Embeddings are a set of models that can convert text into a numerical form, called embedding, which is a numerical representation of the input text. Embeddings make it easier for machines to understand the relationships between words or sentences and can be consumed as inputs by other models, such as classification models, or clustering models that have better performance on numerical data. Embedding models are often used for transfer learning, where a model is built for a surrogate task for which there’s an abundance of data, and then the model weights (embeddings) are re-used for other downstream tasks. An example of this category is [OpenAI embeddings](https://platform.openai.com/docs/models/embeddings?WT.mc_id=academic-105485-koreyst).

![Embedding](./images/Embedding.png?WT.mc_id=academic-105485-koreyst)

Image generation models are models that generate images. These models are often used for image editing, image synthesis, and image translation. Image generation models are often trained on large datasets of images, such as [LAION-5B](https://laion.ai/blog/laion-5b/?WT.mc_id=academic-105485-koreyst), and can be used to generate new images or to edit existing images with inpainting, super-resolution, and colorization techniques. Examples include [DALL-E-3](https://openai.com/dall-e-3?WT.mc_id=academic-105485-koreyst) and [Stable Diffusion models](https://github.com/Stability-AI/StableDiffusion?WT.mc_id=academic-105485-koreyst).

![Image generation](./images/Image.png?WT.mc_id=academic-105485-koreyst)

Text and code generation models are models that generate text or code. These models are often used for text summarization, translation, and question answering. Text generation models are often trained on large datasets of text, such as [BookCorpus](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zhu_Aligning_Books_and_ICCV_2015_paper.html?WT.mc_id=academic-105485-koreyst), and can be used to generate new text, or to answer questions. Code generation models, like [CodeParrot](https://huggingface.co/codeparrot?WT.mc_id=academic-105485-koreyst), are often trained on large datasets of code, such as GitHub, and can be used to generate new code, or to fix bugs in existing code.

![Text and code generation](./images/Text.png?WT.mc_id=academic-105485-koreyst)

### Encoder-Decoder versus Decoder-only

To talk about the different types of architectures of LLMs, let's use an analogy.

Imagine your manager gave you a task for writing a quiz for the students. You have two colleagues; one oversees creating the content and the other oversees reviewing them.

The content creator is like a Decoder only model, they can look at the topic and see what you already wrote and then he can write a course based on that. They are very good at writing engaging and informative content, but they are not very good at understanding the topic and the learning objectives. Some examples of Decoder models are GPT family models, such as GPT-3.

The reviewer is like an Encoder only model, they look at the course written and the answers, noticing the relationship between them and understanding context, but they are not good at generating content. An example of Encoder only model would be BERT.

Imagine that we can have someone as well who could create and review the quiz, this is an Encoder-Decoder model. Some examples would be BART and T5.

### Service versus Model

Now, let's talk about the difference between a service and a model. A service is a product that is offered by a Cloud Service Provider, and is often a combination of models, data, and other components. A model is the core component of a service, and is often a foundation model, such as an LLM.

Services are often optimized for production use and are often easier to use than models, via a graphical user interface. However, services are not always available for free, and may require a subscription or payment to use, in exchange for leveraging the service owner’s equipment and resources, optimizing expenses and scaling easily. An example of a service is [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/overview?WT.mc_id=academic-105485-koreyst), which offers a pay-as-you-go rate plan, meaning users are charged proportionally to how much they use the service Also, Azure OpenAI Service offers enterprise-grade security and a responsible AI framework on top of the models' capabilities.

Models are just the Neural Network, with the parameters, weights, and others. Allowing companies to run locally, however, would need to buy equipment, build a structure to scale and buy a license or use an open-source model. A model like LLaMA is available to be used, requiring computational power to run the model.

## How to test and iterate with different models to understand performance on Azure

Once our team has explored the current LLMs landscape and identified some good candidates for their scenarios, the next step is testing them on their data and on their workload. This is an iterative process, done by experiments and measures.
Most of the models we mentioned in previous paragraphs (OpenAI models, open source models like Llama2, and Hugging Face transformers) are available in the [Model Catalog](https://learn.microsoft.com/azure/ai-studio/how-to/model-catalog-overview?WT.mc_id=academic-105485-koreyst) in [Azure AI Studio](https://ai.azure.com/?WT.mc_id=academic-105485-koreyst).

[Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/what-is-ai-studio?WT.mc_id=academic-105485-koreyst) is a Cloud Platform designed for developers to build generative AI applications and manage the whole development lifecycle - from experimentation to evaluation - by combining all Azure AI services into a single hub with an handy GUI. The Model Catalog in Azure AI Studio enables the user to:

- Find the Foundation Model of interest in the catalog - either proprietary or open source, filtering by task, license, or name. To improve searchability, the models are organized into collections, like Azure OpenAI collection, Hugging Face collection, and more.

![Model catalog](./images/AzureAIStudioModelCatalog.png?WT.mc_id=academic-105485-koreyst)

- Review the model card, including a detailed description of intended use and training data, code samples and evaluation results on the internal evaluations library.

![Model card](./images/ModelCard.png?WT.mc_id=academic-105485-koreyst)

- Compare benchmarks across models and datasets available in the industry to assess which one meets the business scenario, through the [Model Benchmarks](https://learn.microsoft.com/azure/ai-studio/how-to/model-benchmarks?WT.mc_id=academic-105485-koreyst) pane.

![Model benchmarks](./images/ModelBenchmarks.png?WT.mc_id=academic-105485-koreyst)

- Fine-tune the model on custom training data to improve model performance in a specific workload, leveraging the experimentation and tracking capabilities of Azure AI Studio.

![Model fine-tuning](./images/FineTuning.png?WT.mc_id=academic-105485-koreyst)

- Deploy the original pre-trained model or the fine-tuned version to a remote real time inference - managed compute - or serverless api endpoint - [pay-as-you-go](https://learn.microsoft.com/azure/ai-studio/how-to/model-catalog-overview#model-deployment-managed-compute-and-serverless-api-pay-as-you-go?WT.mc_id=academic-105485-koreyst) - to enable applications to consume it.

![Model deployment](./images/ModelDeploy.png?WT.mc_id=academic-105485-koreyst)

> [!NOTE]
> Not all models in the catalog are currently available for fine-tuning and/or pay-as-you-go deployment. Check the model card for details on the model's capabilities and limitations.

## Improving LLM results

We’ve explored with our startup team different kinds of LLMs and a Cloud Platform (Azure Machine Learning) enabling us to compare different models, evaluate them on test data, improve performance and deploy them on inference endpoints.

But when shall they consider fine-tuning a model rather than using a pre-trained one? Are there other approaches to improve model performance on specific workloads?

There are several approaches a business can use to get the results they need from an LLM. You can select different types of models with different degrees of training when deploying an LLM in production, with different levels of complexity, cost, and quality. Here are some different approaches:

- **Prompt engineering with context**. The idea is to provide enough context when you prompt to ensure you get the responses you need.

- **Retrieval Augmented Generation, RAG**. Your data might exist in a database or web endpoint for example, to ensure this data, or a subset of it, is included at the time of prompting, you can fetch the relevant data and make that part of the user's prompt.

- **Fine-tuned model**. Here, you trained the model further on your own data which led to the model being more exact and responsive to your needs but might be costly.

![LLMs deployment](./images/Deploy.png?WT.mc_id=academic-105485-koreyst)

Img source: [Four Ways that Enterprises Deploy LLMs | Fiddler AI Blog](https://www.fiddler.ai/blog/four-ways-that-enterprises-deploy-llms?WT.mc_id=academic-105485-koreyst)

### Prompt Engineering with Context

Pre-trained LLMs work very well on generalized natural language tasks, even by calling them with a short prompt, like a sentence to complete or a question – the so-called “zero-shot” learning.

However, the more the user can frame their query, with a detailed request and examples – the Context – the more accurate and closest to user’s expectations the answer will be. In this case, we talk about “one-shot” learning if the prompt includes only one example and “few shot learning” if it includes multiple examples.
Prompt engineering with context is the most cost-effective approach to kick-off with.

### Retrieval Augmented Generation (RAG)

LLMs have the limitation that they can use only the data that has been used during their training to generate an answer. This means that they don’t know anything about the facts that happened after their training process, and they cannot access non-public information (like company data).
This can be overcome through RAG, a technique that augments prompt with external data in the form of chunks of documents, considering prompt length limits. This is supported by Vector database tools (like [Azure Vector Search](https://learn.microsoft.com/azure/search/vector-search-overview?WT.mc_id=academic-105485-koreyst)) that retrieve the useful chunks from varied pre-defined data sources and add them to the prompt Context.

This technique is very helpful when a business doesn’t have enough data, enough time, or resources to fine-tune an LLM, but still wishes to improve performance on a specific workload and reduce risks of fabrications, i.e., mystification of reality or harmful content.

### Fine-tuned model

Fine-tuning is a process that leverages transfer learning to ‘adapt’ the model to a downstream task or to solve a specific problem. Differently from few-shot learning and RAG, it results in a new model being generated, with updated weights and biases. It requires a set of training examples consisting of a single input (the prompt) and its associated output (the completion).
This would be the preferred approach if:

- **Using fine-tuned models**. A business would like to use fine-tuned less capable models (like embedding models) rather than high performance models, resulting in a more cost effective and fast solution.

- **Considering latency**. Latency is important for a specific use-case, so it’s not possible to use very long prompts or the number of examples that should be learned from the model doesn’t fit with the prompt length limit.

- **Staying up to date**. A business has a lot of high-quality data and ground truth labels and the resources required to maintain this data up to date over time.

### Trained model

Training an LLM from scratch is without a doubt the most difficult and the most complex approach to adopt, requiring massive amounts of data, skilled resources, and appropriate computational power. This option should be considered only in a scenario where a business has a domain-specific use case and a large amount of domain-centric data.

## Knowledge check

What could be a good approach to improve LLM completion results?

1. Prompt engineering with context
1. RAG
1. Fine-tuned model

A:3, if you have the time and resources and high quality data, fine-tuning is the better option to stay up to date. However, if you're looking at improving things and you're lacking time it's worth considering RAG first.

## 🚀 Challenge

Read up more on how you can [use RAG](https://learn.microsoft.com/azure/search/retrieval-augmented-generation-overview?WT.mc_id=academic-105485-koreyst) for your business.

## Great Work, Continue Your Learning

After completing this lesson, check out our [Generative AI Learning collection](https://aka.ms/genai-collection?WT.mc_id=academic-105485-koreyst) to continue leveling up your Generative AI knowledge!

Head over to Lesson 3 where we will look at how to [build with Generative AI Responsibly](../03-using-generative-ai-responsibly/README.md?WT.mc_id=academic-105485-koreyst)!
