# 4D - WHATSAPP BUSINESS API TEMPLATES
## Shubham Solar Solutions - 12 Meta-Approved Templates + Creative Brief
### Category: Marketing / Utility / Authentication | Language: Hindi (hi) + Mewari (raj) Variants

---

## **TEMPLATE ARCHITECTURE**

| Template ID | Category | Funnel Stage | Language | Variables |
|-------------|----------|--------------|----------|-----------|
| `lead_welcome_solar` | Marketing | Lead Capture | Hindi/Mewari | {{name}}, {{city}} |
| `survey_booking` | Utility | Qualification | Hindi/Mewari | {{name}}, {{date}}, {{time}}, {{bda_name}}, {{bda_phone}} |
| `survey_complete_report` | Utility | Post-Survey | Hindi | {{name}}, {{kw_rec}}, {{subsidy_est}}, {{roi_yrs}}, {{pdf_link}} |
| `proposal_shared` | Marketing | Proposal | Hindi | {{name}}, {{option1_kw}}, {{option1_price}}, {{option2_kw}}, {{option2_price}}, {{validity_days}}, {{proposal_link}} |
| `proposal_nudge_1` | Marketing | Follow-up 1 | Hindi/Mewari | {{name}}, {{offer_detail}} |
| `proposal_nudge_2` | Marketing | Follow-up 2 | Hindi/Mewari | {{name}}, {{deadline_date}} |
| `objection_subsidy` | Marketing | Objection Handle | Hindi | {{name}}, {{myth}}, {{fact}} |
| `contract_confirmed` | Utility | Contract | Hindi | {{name}}, {{install_date}}, {{project_id}}, {{pm_name}}, {{pm_phone}} |
| `install_today` | Utility | Install Day | Hindi/Mewari | {{name}}, {{team_lead}}, {{team_phone}}, {{start_time}} |
| `handover_complete` | Utility | Handover | Hindi | {{name}}, {{app_link}}, {{amc_price}}, {{warranty_card_link}} |
| `nps_referral_ask` | Marketing | Referral | Hindi/Mewari | {{name}}, {{referral_code}}, {{reward_amount}} |
| `amc_renewal_reminder` | Marketing | Retention | Hindi | {{name}}, {{expiry_date}}, {{renewal_price}}, {{renewal_link}} |

---

## **TEMPLATE 1: LEAD_WELCOME_SOLAR (Marketing)**

### **Hindi Version**
**Name:** `lead_welcome_solar_hi`
**Header:** Text - "☀️ शुभम सोलर में आपका स्वागत है!"
**Body:**
```
नमस्ते {{name}} जी! 🙏

शुभम सोलर परिवार में आपका स्वागत है।
आपने {{city}} में सोलर के लिए इंक्वायरी की - धन्यवाद!

हम देंगें आपको:
✅ फ्री साइट सर्वे (ड्रोन + शेड एनालिसिस)
✅ PM सूर्य घर सब्सिडी ₹78,000 तक
✅ 25 साल वारंटी + नेट मीटरिंग
✅ EMI बिजली बिल से कम

हमारा BDA {{bda_name}} आपको 15 मिनट में कॉल करेगा।
या अभी व्हाट्सऐप पे चैट करें! 👇
```
**Footer:** "शुभम सोलर - AVVNL एम्पेनल्ड | 7000856261"
**Buttons:** 
- Quick Reply: "सर्वे बुक करें" → `survey_booking`
- Quick Reply: "सब्सिडी जानें" → `subsidy_info`
- URL: "कैलकुलेटर" → https://shubhamsolar.com/solar-calculator

---

### **Mewari Version (Chittorgarh/Udaipur)**
**Name:** `lead_welcome_solar_raj`
**Header:** Text - "☀️ खम्मा घणी! शुभम सोलर पधारो सा!"
**Body:**
```
खम्मा घणी {{name}} सा! 🙏

शुभम सोलर रे परीवार मा आपरो स्वागत है।
थाने {{city}} मा सोलर री जानकारी मांगी - घणो आभार!

अपणी तरफ सूं:
✅ फ्री साइट सर्वे (ड्रोन + शेड चेक)
✅ सरकारी सब्सिडी ₹78,000 तलक
✅ 25 साल वारंटी + नेट मीटरिंग
✅ EMI बिजली बिल सूं कम

अपणो BDA {{bda_name}} थोड़ी देर मा कॉल करसी।
या व्हाट्सऐप पे ही बात करी! 👇
```
**Footer:** "शुभम सोलर - AVVNL एम्पेनल्ड | 7000856261"
**Buttons:** Same as Hindi

---

## **TEMPLATE 2: SURVEY_BOOKING (Utility)**

**Name:** `survey_booking_hi`
**Header:** Text - "📅 फ्री साइट सर्वे बुक्ड - कन्फर्मेशन"
**Body:**
```
{{name}} जी, आपका फ्री साइट सर्वे बुक हो गया! ✅

📅 तारीख: {{date}}
⏰ समय: {{time}}
👨‍🔧 BDA: {{bda_name}} ({{bda_phone}})

तैयारी:
☐ छत की फोटो तैयार रखें
☐ लेटेस्ट बिजली बिल रखें
☐ छत का एक्सेस सुनिश्चित करें

सर्वे में: ड्रोन इंस्पेक्शन, शेड एनालिसिस, मीटर चेक, स्ट्रक्चरल असेसमेंट
कैंसिल/रिशेड्यूल के लिए रिप्लाई करें या कॉल: {{bda_phone}}
```
**Footer:** "शुभम सोलर - समय पे पहुंचेंगे, पक्का वादा"
**Buttons:** Quick Reply: "कन्फर्म" | "रिशेड्यूल" | "कैंसिल"

---

## **TEMPLATE 3: SURVEY_COMPLETE_REPORT (Utility)**

**Name:** `survey_complete_report_hi`
**Header:** Document (PDF) - "साइट सर्वे रिपोर्ट - {{name}}"
**Body:**
```
{{name}} जी, साइट सर्वे पूरा हुआ! 📋

रिपोर्ट अटैच है। मुख्य बातें:
⚡ अनुशंसित सिस्टम: {{kw_rec}} kW
💰 अनुमानित सब्सिडी: ₹{{subsidy_est}}
⏱️ अनुमानित पेबैक: {{roi_yrs}} साल
💵 मासिक बचत: ~₹{{monthly_saving}}/माह

अगला कदम: आपके लिए 3 ऑप्शन का प्रपोजल तैयार कर रहे हैं।
शाम तक व्हाट्सऐप पे मिल जाएगा।

सवाल हों तो बेझिझक पूछें! 👇
```
**Footer:** "PDF रिपोर्ट ऊपर देखें | शुभम सोलर"
**Buttons:** Quick Reply: "प्रपोजल भेजो" | "कॉल बैक" | "सवाल है"

---

## **TEMPLATE 4: PROPOSAL_SHARED (Marketing)**

**Name:** `proposal_shared_hi`
**Header:** Document (PDF) - "आपका कस्टम सोलर प्रपोजल - {{name}}"
**Body:**
```
{{name}} जी, आपका कस्टम प्रपोजल तैयार है! 📄

3 ऑप्शन आपके बजट और जरूरत के हिसाब से:

🥇 **ऑप्शन 1 (सबसे पॉपुलर):** {{option1_kw}} kW - ₹{{option1_price}} (सब्सिडी बाद)
   → बेस्ट वैल्यू, फास्टेस्ट ROI

🥈 **ऑप्शन 2 (प्रीमियम):** {{option2_kw}} kW - ₹{{option2_price}} (सब्सिडी बाद)
   → हाई-एफिशिएंसी पैनल, एक्सटेंडेड वारंटी

🥉 **ऑप्शन 3 (बजट):** {{option3_kw}} kW - ₹{{option3_price}} (सब्सिडी बाद)
   → एंट्री लेवल, अपग्रेडेबल

📅 **वैधता:** {{validity_days}} दिन (सब्सिडी लॉक के लिए)
🔗 **डिटेल PDF:** {{proposal_link}}

कल कॉल करूंगा डिस्कस करने के लिए। कोई सवाल? 👇
```
**Footer:** "कीमत में सब्सिडी घटा के बताई गई है | शुभम सोलर"
**Buttons:** URL: "PDF देखें" → {{proposal_link}} | Quick Reply: "ऑप्शन 1 पसंद" | "ऑप्शन 2 पसंद" | "कॉल करें"

---

## **TEMPLATE 5: PROPOSAL_NUDGE_1 (Marketing)**

**Name:** `proposal_nudge_1_hi`
**Header:** Text - "💡 एक सवाल: {{name}} जी?"
**Body:**
```
प्रपोजल देखा आपने? 

कई ग्राहक पूछते हैं: "सब्सिडी मिलेगी पक्का?"
जवाब: हां! हम AVVNL एम्पेनल्ड हैं, 95%+ अप्रूवल रेट।
सब्सिडी ₹{{subsidy_amt}} आपके खाते में 30-45 दिन में।

आज डिसाइड करें तो:
🎁 इस महीने की सब्सिडी लॉक करवा देंगे
⚡ इंस्टालेशन स्लॉट प्रायोरिटी मिलेगी

कोई डाउट? बस रिप्लाई करें - मैं जवाब दूंगा।
```
**Footer:** "कोई प्रेशर नहीं - बस सही जानकारी देना फर्ज है | शुभम सोलर"
**Buttons:** Quick Reply: "सब्सिडी कन्फर्म करो" | "कॉल बैक" | "ऑप्शन 2 बताओ"

---

## **TEMPLATE 6: PROPOSAL_NUDGE_2 (Marketing) - URGENCY**

**Name:** `proposal_nudge_2_hi`
**Header:** Text - "⏰ {{name}} जी, कल लास्ट डेट है"
**Body:**
```
प्रपोजल की वैलिडिटी कल ({{deadline_date}}) खत्म हो रही है।

इसके बाद:
❌ सब्सिडी स्लॉट रिलीज हो सकता है
❌ इंस्टालेशन स्लॉट अगले महीने शिफ्ट होगा
❌ पैनल प्राइस रिवीजन का रिस्क

अभी कन्फर्म करें तो:
✅ सब्सिडी लॉक्ड
✅ इंस्टालेशन डेट फिक्स्ड
✅ करंट प्राइस गारंटीड

सिर्फ "हां" रिप्लाई करें - बाकी हम संभाल लेंगे। 🤝
```
**Footer:** "आखिरी मौका - सब्सिडी सिक्योर करने का | शुभम सोलर"
**Buttons:** Quick Reply: "हां, कन्फर्म" | "कॉल मी" | "एक दिन और"

---

## **TEMPLATE 7: OBJECTION_SUBSIDY (Marketing)**

**Name:** `objection_subsidy_hi`
**Header:** Text - "🤔 {{name}} जी, सब्सिडी का डाउट क्लियर करते हैं"
**Body:**
```
सुना है: "{{myth}}"

सच्चाई: {{fact}}

उदाहरण: चित्तौड़गढ़ के शर्मा जी को 3kW पे ₹78,000 सब्सिडी 28 दिन में मिली।
हमारे 200+ केस में 95% सब्सिडी अप्रूव हुई।

हम करते हैं:
✅ DISCOM पोर्टल पे फाइलिंग
✅ डॉक्यूमेंट वेरिफिकेशन
✅ फॉलो-अप टिल अप्रूवल
✅ पैसा खाते में ट्रैक करना

आपको बस साइन करना है। बाकी हमारा सरदर्द। 😊
```
**Footer:** "सब्सिडी एक्सपर्ट = शुभम सोलर | 7000856261"
**Buttons:** Quick Reply: "प्रूफ दिखाओ" | "कॉल करके समझाओ" | "ठीक है, आगे बढ़ो"

---

## **TEMPLATE 8: CONTRACT_CONFIRMED (Utility)**

**Name:** `contract_confirmed_hi`
**Header:** Text - "🎉 {{name}} जी, कॉन्ट्रैक्ट साइन - वेलकम टू सोलर!"
**Body:**
```
बधाई हो! आपका सोलर सफर शुरू। 🎊

📋 प्रोजेक्ट ID: {{project_id}}
📅 इंस्टालेशन डेट: {{install_date}}
👨‍🔧 प्रोजेक्ट मैनेजर: {{pm_name}} ({{pm_phone}})

अगले स्टेप्स:
1️⃣ नेट मीटरिंग एप्लीकेशन (हम करेंगे)
2️⃣ सब्सिडी पोर्टल फाइलिंग (हम करेंगे)
3️⃣ मैटेरियल डिलीवरी (इंस्टाल से 2 दिन पहले)
4️⃣ इंस्टालेशन ({{install_date}} को)

कुछ चाहिए? {{pm_name}} को डायरेक्ट कॉल/व्हाट्सऐप करें।
```
**Footer:** "शुभम सोलर - अब आपकी बिजली, आपका कंट्रोल | 7000856261"
**Buttons:** Quick Reply: "थैंक्स" | "PM से बात करनी है" | "डॉक्यूमेंट चेकलिस्ट"

---

## **TEMPLATE 9: INSTALL_TODAY (Utility)**

**Name:** `install_today_hi`
**Header:** Text - "🚛 आज इंस्टालेशन डे है, {{name}} जी!"
**Body:**
```
गुड मॉर्निंग! आज आपकी छत पे सोलर लग रहा है। ☀️

👷 टीम लीड: {{team_lead}} ({{team_phone}})
⏰ पहुंच रहे: {{start_time}} बजे
📦 मैटेरियल: पैनल, इन्वर्टर, स्ट्रक्चर - सब पहुंच गया

आपको बस:
☐ छत का एक्सेस देना
☐ मीटर रूम दिखाना
☐ चाय/पानी (ऑप्शनल! 😄)

दिन भर अपडेट मिलते रहेंगे। शाम को कमीशनिंग फोटो भेजूंगा।
```
**Footer:** "शुभम सोलर - काम चालू, पक्का वादा | 7000856261"
**Buttons:** Quick Reply: "पहुंच गए" | "थोड़ा लेट" | "सवाल है"

---

## **TEMPLATE 10: HANDOVER_COMPLETE (Utility)**

**Name:** `handover_complete_hi`
**Header:** Document (PDF) - "कमीशनिंग सर्टिफिकेट - {{name}}"
**Body:**
```
{{name}} जी, बधाई! आपका सोलर लाइव है! 🎉⚡

✅ कमीशनिंग पूरी
✅ नेट मीटरिंग एक्टिव (मीटर उल्टा घूम रहा!)
✅ ऐप सेटअप: जेनरेशन/खपत ट्रैक करें
🔗 ऐप लिंक: {{app_link}}

📋 वारंटी कार्ड: {{warranty_card_link}}
🛡️ AMC ऑफर: ₹{{amc_price}}/kW/साल (सफाई + चेकअप)
   → पहले साल फ्री अगर आज कन्फर्म करें

गूगल रिव्यू देंगे? 2 मिनट: g.co/kgs/ShubhamSolar
```
**Footer:** "आपकी बचत शुरू! शुभम सोलर - 7000856261"
**Buttons:** URL: "ऐप डाउनलोड" → {{app_link}} | Quick Reply: "AMC लेनी है" | "रिव्यू दूंगा" | "थैंक्स"

---

## **TEMPLATE 11: NPS_REFERRAL_ASK (Marketing)**

**Name:** `nps_referral_ask_hi`
**Header:** Text - "❤️ {{name}} जी, कैसा लगा एक्सपीरियंस?"
**Body:**
```
1-10 स्केल पे रेट करें: हमारा काम कैसा रहा?

रिप्लाई में नंबर लिखें (1-10)।

और हां - अगर खुश हैं तो:
🎁 रेफरल कोड: {{referral_code}}
💰 हर इंस्टाल पे: ₹{{reward_amount}} कैशबैक
👯‍♂️ दोस्त/रिश्तेदार को शेयर करें

उनको: फ्री सर्वे + प्रायोरिटी सब्सिडी
आपको: ₹{{reward_amount}}/इंस्टाल (अनलिमिटेड!)

कोड शेयर करें: "शुभम सोलर से सोलर लगवाया, {{referral_code}} यूज करो"
```
**Footer:** "रेफरल अनलिमिटेड - जितने लगवाओ, उतना कमाओ | शुभम सोलर"
**Buttons:** Quick Reply: "10/10 - शेयर करूंगा" | "8/10 - कॉल करो" | "बाद में"

---

## **TEMPLATE 12: AMC_RENEWAL_REMINDER (Marketing)**

**Name:** `amc_renewal_reminder_hi`
**Header:** Text - "🔧 {{name}} जी, AMC रिन्यूअल का समय"
**Body:**
```
आपका AMC {{expiry_date}} को एक्सपायर हो रहा है।

रिन्यू कराएं और पाएं:
✅ साल में 2 प्रोफेशनल सफाई
✅ इन्वर्टर/पैनल हेल्थ चेकअप
✅ प्रायोरिटी ब्रेकडाउन सपोर्ट (24hr)
✅ जेनरेशन गारंटी चेक

💰 प्राइस: ₹{{renewal_price}} (पिछले साल जितना)
🔗 ऑनलाइन रिन्यू: {{renewal_link}}

लैप्स होने पर: ब्रेकडाउन चार्ज डबल, वारंटी क्लेम में दिक्कत।
```
**Footer:** "AMC = सुकून की नींद | शुभम सोलर - 7000856261"
**Buttons:** URL: "अभी रिन्यू करें" → {{renewal_link}} | Quick Reply: "कॉल बैक" | "व्हाट्सऐप पे पेमेंट"

---

## **MEWARI VARIANTS (Key Templates Only)**

### **survey_booking_raj (Mewari)**
```
{{name}} सा, फ्री साइट सर्वे बुक होग्यो! ✅

📅 तारीख: {{date}}
⏰ समय: {{time}}
👨‍🔧 म्हारो BDA: {{bda_name}} ({{bda_phone}})

तैयारी राखो:
☐ छत री फोटो
☐ बिजली बिल
☐ छत रो रास्तो खुल्लो

सर्वे मा: ड्रोन, शेड चेक, मीटर, स्ट्रक्चर
कैंसिल/रिशेड्यूल करे तो रिप्लाई कर दो।
```

### **install_today_raj (Mewari)**
```
सुप्रभात {{name}} सा! आज इंस्टालेशन है! ☀️

👷 टीम: {{team_lead}} ({{team_phone}})
⏰ {{start_time}} बजे पहुंचसी
📦 सामान सब आ गयो

थाने बस छत खोल देनी, मीटर दिखा देनी।
दिन भर खबर देसी रहूंगा। शाम ने फोटो भेजसी।
```

### **nps_referral_ask_raj (Mewari)**
```
{{name}} सा, कैसो लग्यो अपणो काम? 1-10 मा बताओ।

खुश हो तो:
🎁 कोड: {{referral_code}}
💰 ₹{{reward_amount}}/इंस्टाल - अनलिमिटेड!

साथी/रिश्तेदार ने बोलो: "शुभम सोलर, कोड {{referral_code}}"
```

---

## **CREATIVE BRIEF FOR DESIGN/VIDEO TEAM**

### **Brand Visual Identity**
| Element | Specification |
|---------|---------------|
| **Primary Colors** | Solar Orange (#FF6B00), Sky Blue (#00A8E8), White (#FFFFFF) |
| **Secondary** | Dark Charcoal (#1A1A2E), Green (#00C853) |
| **Typography** | Headlines: Poppins Bold | Body: Inter Regular | Hindi: Noto Sans Devanagari |
| **Logo Usage** | Min 24px clear space, never on busy backgrounds |
| **Watermark** | "शुभम सोलर" bottom-right 15% opacity on all creatives |

### **Static Ad Creative Templates**

| Template | Dimensions | Elements |
|----------|------------|----------|
| **Hero_Bill_Comparison** | 1080x1080, 1080x1350 | Left: "पहले" (Red bill ₹4,500) → Right: "बाद" (Green bill ₹0) + Solar roof |
| **Subsidy_Math** | 1080x1080 | Large "₹78,000" center, "सरकारी सब्सिडी" below, "300 यूनिट मुफ्त" badge |
| **Neighbor_Proof** | 1080x1080 | Split: Neighbor's roof with solar → "पड़ोस री छत" | Your roof empty → "आपणी पे काय ना?" |
| **EMI_vs_Bill** | 1080x1080 | Calculator screen: "EMI: ₹2,499" vs "Bill: ₹4,500" → "बचत: ₹2,000/माह" |
| **Install_Timelapse** | 1080x1080 | 3 panels: Day 1 (Structure) → Day 2 (Panels) → Day 3 (Live) + "3 दिन, काम पूरा" |
| **Trust_Badges** | 1080x1080 | Grid: AVVNL Empaneled | 2000+ Installs | 25yr Warranty | Varee/Adani Partner | 4.9★ |

### **Video Creative Specs (Reels/Stories - 9:16)**

| Video | Duration | Script Outline |
|-------|----------|----------------|
| **BDA_Intro_Mewari** | 15s | BDA on bike → "खम्मा घणी! मैं {{name}} शुभम सोलर से..." → shows calculator → "फ्री सर्वे बुक करो" |
| **Customer_Testimonial** | 30s | Customer at home → shows old bill → shows new bill ₹0 → "सब्सिडी ₹78k मिली" → "आप भी लगाओ" |
| **Install_Timelapse** | 20s | Drone: empty roof → structure → panels → inverter → meter spinning backward → "3 दिन" |
| **Subsidy_Explainer** | 25s | Animation: "फॉर्म भरो → हम चेक करते → DISCOM सबमिट → पैसा खाते में" → "कागज हम संभालते" |
| **Agri_Pump_Demo** | 30s | Farmer starts pump → water flows → "डीजल बंद, सोलर चालू" → shows subsidy math → "किसान भाई, फ्री सर्वे" |
| **Commercial_ROI** | 25s | Factory/hotel roof → graph: "Bill ₹15L → ₹7.5L" → "4.2yr payback" → "Green certified" |

### **WhatsApp Catalog Products (5 Items)**

| Product ID | Name | Price | Description (Hindi) | Image |
|------------|------|-------|---------------------|-------|
| `SSS_1KW_ON` | 1kW ऑन-ग्रिड | ₹75,000 | छोटे घर के लिए, 150-200 यूनिट/माह, सब्सिडी ₹30,000 | 1kw_system.jpg |
| `SSS_3KW_ON` | 3kW ऑन-ग्रिड | ₹1,80,000 | 3BHK के लिए बेस्ट, 350-450 यूनिट/माह, सब्सिडी ₹78,000 | 3kw_system.jpg |
| `SSS_5KW_ON` | 5kW ऑन-ग्रिड | ₹3,00,000 | बड़े घर/छोटी दुकान, 600-750 यूनिट/माह, सब्सिडी ₹78,000 | 5kw_system.jpg |
| `SSS_10KW_ON` | 10kW ऑन-ग्रिड | ₹5,50,000 | कमर्शियल/बड़ा घर, 1200-1500 यूनिट/माह, नेट मीटरिंग | 10kw_system.jpg |
| `SSS_3HP_PUMP` | 3HP सोलर पंप | ₹2,50,000 | PM-KUSUM 60% सब्सिडी, 3-4 बीघा सिंचाई, डीजल फ्री | 3hp_pump.jpg |

---

## **TEMPLATE APPROVAL CHECKLIST (Meta Business Manager)**

### **Pre-Submission**
- [ ] All variables use `{{variable_name}}` format (lowercase, underscore)
- [ ] Header: Text/Image/Video - only ONE type per template
- [ ] Body: ≤1024 chars, max 10 variables
- [ ] Footer: ≤60 chars, no variables
- [ ] Buttons: ≤3 quick reply OR 2 URL + 1 phone OR 1 URL + 1 phone + 1 QR
- [ ] Language code: `hi` for Hindi, `raj` for Rajasthani/Mewari (if supported) else `hi`
- [ ] Category correct: Marketing (promo) vs Utility (transactional)

### **Submission Process**
1. Go to Meta Business Manager → WhatsApp Manager → Message Templates
2. Click "Create Template" → Select Category → Fill form
3. Submit for review (usually 1-24 hours)
4. Track status: `PENDING` → `APPROVED` / `REJECTED`
5. If rejected: Fix issue → Resubmit

### **Common Rejection Reasons & Fixes**
| Reason | Fix |
|--------|-----|
| "Promotional in Utility" | Move to Marketing category or remove sales language |
| "Variable in Footer" | Remove variables from footer |
| "Too many variables" | Reduce to ≤10 in body |
| "Misleading content" | Remove guarantees like "100% subsidy approved" |
| "Language mismatch" | Ensure template language matches selected code |

---

## **INTEGRATION WITH ZOHO CRM**

### **Webhook Events to Track**
```json
{
  "event": "message_sent",
  "template": "proposal_shared",
  "contact": "{{contact_id}}",
  "deal": "{{deal_id}}",
  "timestamp": "2026-10-15T10:30:00Z"
}
```

### **Automation Flows**
| Trigger | Action | Template |
|---------|--------|----------|
| Lead Created (Zoho Form) | Send Welcome | `lead_welcome_solar` |
| Survey Booked (CRM) | Send Confirmation | `survey_booking` |
| Survey Completed (Field App) | Send Report | `survey_complete_report` |
| Proposal Generated (CRM) | Send PDF | `proposal_shared` |
| Proposal Stale 3 days | Nudge 1 | `proposal_nudge_1` |
| Proposal Stale 7 days | Nudge 2 (Urgency) | `proposal_nudge_2` |
| Objection Logged: "Subsidy" | Send Myth/Fact | `objection_subsidy` |
| Contract Signed | Confirm + Next Steps | `contract_confirmed` |
| Install Scheduled (1 day prior) | Reminder | `install_today` |
| Commissioned (Field App) | Handover + AMC | `handover_complete` |
| NPS Survey Sent (Day 7) | Referral Ask | `nps_referral_ask` |
| AMC Expiry (30 days prior) | Renewal Reminder | `amc_renewal_reminder` |

---

## **METRICS TO TRACK (Weekly Dashboard)**

| Template | Sent | Delivered | Read | Replied | Conversion | Opt-out |
|----------|------|-----------|------|---------|------------|---------|
| lead_welcome | | | | | Lead→Survey | |
| survey_booking | | | | Confirm% | Show-up% | |
| survey_report | | | | Question% | Survey→Proposal | |
| proposal_shared | | | | Open% | Proposal→Contract | |
| proposal_nudge_1 | | | | Reply% | Re-engagement | |
| proposal_nudge_2 | | | | Reply% | Urgency Close | |
| objection_subsidy | | | | Reply% | Objection→Close | |
| contract_confirmed | | | | Ack% | Contract→Install | |
| install_today | | | | Ack% | Install Attendance | |
| handover_complete | | | | App% | AMC Attach% | |
| nps_referral | | | | NPS Score | Referrals Generated | |
| amc_renewal | | | | Click% | Renewal Rate | |

---

## **COMPLIANCE & BEST PRACTICES**

### **Opt-in Management**
- [ ] Website form: Explicit "WhatsApp updates" checkbox (unchecked by default)
- [ ] Offline: Verbal consent logged in CRM
- [ ] First message: Always `lead_welcome` (Marketing) - establishes thread
- [ ] Opt-out: "STOP" keyword → Auto-unsubscribe + CRM flag

### **Frequency Capping**
- Marketing: Max 3/week per contact
- Utility: No cap (transactional)
- No messages 9PM-8AM (IST)

### **Data Retention**
- Chat logs: 2 years (compliance)
- Media files: 30 days (auto-purge)
- PII: Encrypted at rest, access logged

---

*Document Version: 1.0 | Created: October 2026 | For: Shubham Solar Solutions WhatsApp Business API Launch*