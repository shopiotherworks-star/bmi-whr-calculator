# 🩺 Clinical Metrics Calculator: BMI, WHR, & IBW for Asian population

An interactive, client-side web application engineered to calculate and evaluate key physiological health indicators. Designed with responsive layouts and strict validation logic for use in educational and health screening environments.

## 🔗 Live Application
👉 [Click here to view the live interactive calculator](https://github.com/shopiotherworks-star/bmi-whr-calculator/settings/pages)

## 🛠️ Features & Methodology
* **BMI Assessment:** Evaluates Body Mass Index dynamically adjusted to the **World Health Organization (WHO) Asian Classification Standards** ($18.5 - 22.9$ for optimal ranges) to account for distinct metabolic risk variations.
* **Ideal Body Weight (IBW):** Computes weight targets utilizing the classic **Devine Formula (1974)**, fortified with dynamic floor-bounding logic to prevent mathematical scaling anomalies for individuals under 5 feet tall.
* **Waist-to-Hip Ratio (WHR):** Assesses body fat distribution patterns against gender-stratified cardiovascular risk thresholds ($0.88$ for males, $0.81$ for females).
* **Data Portability:** Features a client-side text generation system enabling users to download localized, formatted text copies of their assessment profiles.

## 💻 Tech Stack
* **Markup & UI Structure:** HTML5
* **Styling Framework:** Custom CSS3 Flexbox (Responsive Design)
* **Logic Engine:** Vanilla JavaScript (ES6+)

## 📚 References
* Devine, B.J., 1974. Gentamicin therapy. *Drug Intelligence & Clinical Pharmacy*, 8(10), pp.650–655.
* World Health Organization, 2004. Appropriate body-mass index for Asian populations and its implications for policy and intervention strategies. *The Lancet*.
