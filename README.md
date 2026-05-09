# Field Workforce Scheduling — Interactive Lesson

> درس تفاعلي ثنائي اللغة (عربي/إنجليزي) لطلاب علوم الحاسب والهندسة الصناعية، يشرح مشكلة جدولة القوى العاملة الميدانية وحلولها بالذكاء الاصطناعي.
>
> A bilingual interactive lesson (Arabic/English) for CS and IE undergraduates, explaining the Field Workforce Scheduling problem and its AI-driven solutions.

🌐 **[View the lesson live](https://USERNAME.github.io/fws-lesson/)**

---

## ✨ Features | المزايا

- **Bilingual** — full Arabic/English toggle with RTL/LTR layout switching
- **8 chapters** — from problem definition to working code
- **3 interactive simulators** — combinatorial complexity, VRP map solver, constraint impact
- **Mathematical formulation** — complete MILP with sets, variables, objective, and constraints
- **Working code examples** — Python implementations using OR-Tools (CP-SAT) and a genetic algorithm
- **Real-world examples** — UPS, Uber, Aramco, STC
- **Self-assessment quiz** — 6 questions with detailed feedback

---

## 📚 Contents | المحتوى

| Chapter | Topic | الموضوع |
|---|---|---|
| 01 | The problem | المشكلة |
| 02 | Mathematical formulation (MILP) | الصياغة الرياضية |
| 03 | Hard vs soft constraints | القيود الصارمة واللينة |
| 04 | Four AI approaches | أربع طرق ذكاء اصطناعي |
| 05 | Interactive simulators | محاكيات تفاعلية |
| 06 | Code examples | أمثلة برمجية |
| 07 | Real-world systems | أنظمة واقعية |
| 08 | Quiz | اختبار |

---

## 🚀 Local Preview | المعاينة المحلية

The page is a single self-contained HTML file. Just open it in any modern browser:

```bash
# Option 1: open directly
open index.html

# Option 2: serve via Python
python3 -m http.server 8000
# then visit http://localhost:8000
```

No build step, no dependencies, no installation.

---

## 🛠 Technical Stack | المكدس التقني

- Pure HTML / CSS / JavaScript — no frameworks
- Canvas API for all simulators (no charting libraries)
- Google Fonts: Cormorant Garamond, Inter, JetBrains Mono, Tajawal, Amiri
- Design philosophy: *Editorial Academia* — deep forest green, cream, burnt orange

---

## 📝 License | الترخيص

Educational use. Adapt and remix freely for teaching.

---

## 🎓 For Instructors | للمدرّسين

This page is designed for a **30-45 minute lecture** for undergraduate CS/IE students. Suggested flow:

1. Open with a brainstorm: *"How would you assign 30 technicians to 200 jobs?"*
2. Walk through chapters 01-04 (problem, math, constraints, algorithms) — about 20 minutes
3. Hand over to the simulators in chapter 05 — let students experiment for 10 minutes
4. Discuss the code in chapter 06 briefly — assign as homework
5. Wrap up with the quiz in chapter 08 — students self-assess

---

Built with care for the Deanship of Admission and Registration teaching program.
