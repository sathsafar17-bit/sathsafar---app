SathSafar — GitHub Upload & APK Build Guide (हिंदी)

यह गाइड बताती है कि कैसे आप इस पैकेज को GitHub पर अपलोड करके auto‑build से APK डाउनलोड कर सकते हैं.

स्टेप 1 — ZIP निकालें (unzip)
1. sathsafar_github_package.zip डाउनलोड कर लें और extract करें.

स्टेप 2 — GitHub पर नया repo बनाएँ
1. https://github.com/new पर जाएँ और repo नाम `sathsafar-app` रखें.
2. Public रखें और Create करें.

स्टेप 3 — फ़ाइलें अपलोड करें (Drag & Drop)
1. अपने नए repo के अंदर Add file → Upload files चुनें.
2. Extracted फ़ोल्डर की सारी फाइलें (सब फ़ोल्डर्स सहित) select करके drag करके box में डालें.
3. नीचे Commit changes पर क्लिक करें.

स्टेप 4 — Workflow सेट करें
इस पैकेज में `.github/workflows/flutter-build.yml` पहले से मौजूद है — आपको कुछ नहीं बदलना है.

स्टेप 5 — Push या Commit करें
1. अब repo में कोई छोटा बदलाव कर के commit करें (README में एक लाइन जोड़ दें) — इससे Action शुरू हो जाएगी.

स्टेप 6 — Actions देखें और APK डाउनलोड करें
1. Repo में "Actions" टैब खोलें.
2. Build workflow पर क्लिक करें। चलने के बाद "Artifacts" में `sathsafar-app-release` मिलेगा — उस पर क्लिक कर के APK डाउनलोड कर लें.

Demo login details:
- मोबाइल: 9999999999 (auto-verify)
- OTP: 123456

Support:
- फोन: +91-9999999999
- ईमेल: support@sathsafar.in
- वेबसाइट: https://www.sathsafar.in
