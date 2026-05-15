<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manar Mohamed | Nursing Quiz Bank</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap');
        :root { --rose-taupe: #b08d8d; --mint-green: #c1d9d1; --beige: #e9dcc9; --dark: #4a3f35; }
        body { font-family: 'Tajawal', sans-serif; background-color: var(--beige); margin: 0; padding: 0; display: flex; justify-content: center; }
        .mobile-wrapper { width: 100%; max-width: 450px; background: var(--beige); min-height: 100vh; padding: 20px; box-sizing: border-box; }
        .header-card { background: var(--rose-taupe); border-radius: 20px; padding: 30px 15px; text-align: center; color: white; margin-bottom: 25px; box-shadow: 0 8px 20px rgba(141, 117, 117, 0.2); }
        .whatsapp-btn { display: block; background-color: #457b9d; color: white; text-align: center; padding: 15px; border-radius: 12px; text-decoration: none; font-weight: bold; margin-bottom: 25px; }
        .nav-list { display: flex; flex-direction: column; gap: 10px; }
        .nav-item { background: #f4eee5; border: 2px solid var(--rose-taupe); padding: 15px; border-radius: 15px; color: var(--dark); font-weight: bold; cursor: pointer; display: flex; justify-content: space-between; }
        #quiz-page { display: none; }
        .back-link { color: var(--rose-taupe); text-decoration: none; font-weight: bold; display: block; margin-bottom: 15px; }
        .question-box { background: var(--mint-green); border: 1px solid #a6beba; padding: 18px; border-radius: 15px; margin-bottom: 15px; }
        .option { background: #fdf8f1; border: 1.5px solid var(--rose-taupe); padding: 12px; margin: 8px 0; border-radius: 10px; cursor: pointer; }
        .correct { background: #2d6a4f !important; color: white !important; }
        .wrong { background: #d62828 !important; color: white !important; }
    </style>
</head>
<body>

<div class="mobile-wrapper">
    <div id="main-menu">
        <div class="header-card">
            <h1>بنك أسئلة البالغين</h1>
            <div style="font-size: 0.9rem; margin-top: 10px;">إعداد  مــنــار مــحـمـد</div>
        </div>
        <a href="https://chat.whatsapp.com/KJd81GD8LBSGSqAU3KaOwX" class="whatsapp-btn">جروب الواتساب 💬</a>
        <div class="nav-list" id="menu-items"></div>
    </div>

    <div id="quiz-page">
        <a href="javascript:void(0)" class="back-link" onclick="closePage()">← رجوع للقائمة</a>
        <h2 id="quiz-title" style="color: var(--rose-taupe); text-align: center;"></h2>
        <div id="questions-area"></div>
    </div>
</div>

<script>
// 1. مصفوفات الأسئلة (كل الداتا اللي جمعناها بالمللي)

const mid2026Questions = [
    { q: "Lumbar puncture is used to determine the underlying cause of increased ICP.", options: ["True", "False"], answer: "False" },
    { q: "Increased water content of urine is a sign of diuretic phase of acute renal failure.", options: ["True", "False"], answer: "True" },
    { q: "The presence of thrill (vibration) in the site of arteriovenous fistula site indicates major Complication.", options: ["True", "False"], answer: "False" },
    { q: "Classic symptom of transient ischemic attack is feeling blindness in one eye.", options: ["True", "False"], answer: "True" },
    { q: "Osmosis is movement of particles from greater to lesser concentration.", options: ["True", "False"], answer: "False" },
    { q: "Traction is the application of a pulling force to a part of the body.", options: ["True", "False"], answer: "True" },
    { q: "Medications to reduce Cerebral edema include mannitol.", options: ["True", "False"], answer: "True" },
    { q: "Increased ICP is sudden loss of function from disruption of blood supply.", options: ["True", "False"], answer: "False" },
    { q: "Acute flexion or rotation of neck should be applied for aneurysm precaution.", options: ["True", "False"], answer: "False" },
    { q: "Erythropoietin used for treatment of hypercalcemia in CRF.", options: ["True", "False"], answer: "False" },
    { q: "Etiology of elevated ICP include tumors and aneurysm.", options: ["True", "False"], answer: "True" },
    { q: "IV sodium bicarbonate treats metabolic alkalosis in CRF.", options: ["True", "False"], answer: "False" },
    { q: "Complications of increased ICP include seizures & brain stem herniation.", options: ["True", "False"], answer: "True" },
    { q: "Isometric exercises are encouraged to minimize disuse atrophy.", options: ["True", "False"], answer: "True" },
    { q: "To maintain airway in elevated ICP, coughing is encouraged.", options: ["True", "False"], answer: "False" },
    { q: "Open fracture refers to broken bone without skin injury.", options: ["True", "False"], answer: "False" },
    { q: "Clinical manifestations of stroke include projectile vomiting and seizure.", options: ["True", "False"], answer: "True" },
    { q: "Hypotension is a short-term complication of hemodialysis.", options: ["True", "False"], answer: "True" },
    { q: "Circulation impairment in traction is manifested by cold skin.", options: ["True", "False"], answer: "True" },
    { q: "Aneurysm precautions include ambulation training.", options: ["True", "False"], answer: "False" },
    { q: "A craniotomy is performed to remove tumor or evacuate blood clot.", options: ["True", "False"], answer: "True" },
    { q: "Early changes in LOC are manifestations of hemorrhagic stroke.", options: ["True", "False"], answer: "True" },
    { q: "ICP is defined as cerebral fluid pressure greater than 30 mm Hg.", options: ["True", "False"], answer: "False" },
    { q: "Aphasia is inability to perform purposeful movements.", options: ["True", "False"], answer: "False" },
    { q: "Diet high in potassium and phosphorus is recommended for CRF.", options: ["True", "False"], answer: "False" },
    { q: "Acidosis is common in patients with renal failure.", options: ["True", "False"], answer: "True" },
    { q: "Crepitus occurs due to compression of the nerve.", options: ["True", "False"], answer: "False" },
    { q: "Early complications of fracture include avascular necrosis.", options: ["True", "False"], answer: "True" },
    { q: "Patient with diabetes is at most risk for?", options: ["Hemorrhagic stroke", "Brain tumor", "Ischemic stroke", "Cerebral aneurysm"], answer: "c" },
    { q: "Strategy to reduce factors contributing to elevation of ICP?", options: ["Flexing hips", "Rotating head", "Neutral midline position", "Frequent coughing"], answer: "c" },
    { q: "Reason to void before peritoneal dialysis catheter insertion?", options: ["Measure output", "Prevent bladder puncture", "Prevent infection", "Comfort"], answer: "b" },
    { q: "Maintain cerebral perfusion in increased ICP, EXCEPT:", options: ["IV fluids", "Inotropic agents", "Keep patient flat", "Osmotic diuretics"], answer: "c" },
    { q: "Effective action in preventing increased ICP during suctioning?", options: ["Hyperoxygenating with 100% O2", "Suction for 30s", "High pressure suction", "Suction every 10m"], answer: "a" },
    { q: "Mechanism of Ischemic stroke?", options: ["Rupture of vessel", "Hemorrhage", "Hypertension", "Thrombus/embolism obstructing supply"], answer: "d" },
    { q: "Type of fixation using screws and plates internally?", options: ["ORIF", "Closed reduction", "External fixation", "Skin traction"], answer: "a" },
    { q: "Main goal of reduction in fracture treatment?", options: ["Reduce pain", "Stop bleeding", "Restore anatomic alignment", "Apply cast"], answer: "c" },
    { q: "Severe pain, numbness, and absent pulse indicate?", options: ["Fat embolism", "Infection", "Compartment Syndrome", "Muscle spasm"], answer: "c" },
    { q: "Contraindication for lumbar puncture in SAH?", options: ["Increased ICP", "Elderly", "Low BP", "Severe headache"], answer: "a" },
    { q: "Surgical opening of skull above the tentorium?", options: ["Infratentorial", "Transsphenoidal", "Supratentorial", "Burr holes"], answer: "c" },
    { q: "Bleeding into brain tissue due to spontaneous rupture?", options: ["Hemorrhagic Stroke", "TIA", "Ischemic stroke", "Abscess"], answer: "a" },
    { q: "First action for cast patient with numbness/cold toes?", options: ["Notify doctor", "Pain meds", "Assess neurovascular status", "Elevate limb"], answer: "c" },
    { q: "Water movement in dialysis due to concentration gradient?", options: ["Diffusion", "Osmosis", "Ultrafiltration", "Convection"], answer: "b" },
    { q: "Indication of ineffective skin traction?", options: ["Weights free", "Straight pull", "Weights resting on floor", "Alignment"], answer: "c" },
    { q: "Why is mannitol ordered for stroke patient with dilated pupils?", options: ["Lower BP", "Decrease ICP via diuresis", "Infection", "Stop bleeding"], answer: "b" },
    { q: "Feeling a vibration over the fistula is called?", options: ["Bruit", "Murmur", "Thrill", "Pulse"], answer: "c" },
    { q: "Primary purpose of recording weight before hemodialysis?", options: ["Nutrition", "Determine fluid to remove", "Height", "Obesity"], answer: "b" },
    { q: "Correct statement about peritoneal dialysis?", options: ["Machine filter", "Requires fistula", "Peritoneum is natural filter", "4 hours only"], answer: "c" },
    { q: "Phase of ARF with increasing urine but high BUN/Cr?", options: ["Oliguric", "Recovery", "Diuretic", "Initiation"], answer: "c" },
    { q: "Primary risk factor for stroke?", options: ["Diabetes", "Hypertension", "Obesity", "Smoking"], answer: "b" },
    { q: "Maximum duration for suctioning?", options: ["5s", "10s", "15s", "30s"], answer: "c" },
    { q: "Position after supratentorial surgery?", options: ["Flat", "Trendelenburg", "Head elevated 30 degrees", "Prone"], answer: "c" }
];
const mid2025Questions = [
    { q: "After cast application the nurse should assess the circulation, sensation, and mobility of the affected part every:", options: ["A) Every 24 hours", "B) Every 6 hours", "C) Every 12 hours", "D) Every 1 to 2 hours"], answer: "d" },
    { q: "The nurse instructs the patient with a lower limb cast to do simple exercises for the affected part by contraction and relaxation of the muscles without joint movement. What is the type of these exercises?", options: ["A) Isotonic exercises", "B) Range of Motion exercises", "C) Isometric exercises", "D) All of the above"], answer: "c" },
    { q: "Mr. Ahmed came to the outpatient clinic for follow-up of an external fixation device in the left lower limb. What is the important point that the nurse should assess?", options: ["A) Pin site infection", "B) Ability of bearing down on his limb", "C) Healing process of the fracture", "D) The nutritional status"], answer: "a" },
    { q: "Crepitus is one of the clinical manifestations of fracture. Which of the following is true about crepitus?", options: ["A) It is caused by the rubbing of bone fragments against each other", "B) It occurs due to contraction of the muscle", "C) It occurs due to compression of the nerve", "D) It is due to rupture of small blood vessels"], answer: "a" },
    { q: "You're providing education to a patient about how to take their prescribed iron supplement. Which statement by the patient requires you to re-educate them?", options: ["A) I will take this medication on an empty stomach.", "B) I will take this medication with orange juice.", "C) I will avoid taking antacids.", "D) I will take it with milk to avoid stomach upset"], answer: "d" }, // تم تعديل الخيار D ليكون هو الخطأ علمياً لأن الكالسيوم يعيق الامتصاص
    { q: "Which of the following can result in megaloblastic anemia?", options: ["A) Certain toxic materials", "B) Red cell destruction", "C) Vitamin B-12 and folic acid deficiency", "D) Infection"], answer: "c" },
    { q: "AV fistula is a surgical connection between an artery and a vein lying in close proximity.", options: ["True", "False"], answer: "True" },
    { q: "Nerve damage is a potential complication of skin traction.", options: ["True", "False"], answer: "True" },
    { q: "Malignancy can cause anemia in chronic disease.", options: ["True", "False"], answer: "True" },
    { q: "Break of bone with open wound:", options: ["A) Compound fracture", "B) Complete fracture", "C) Spiral fracture", "D) Linear fracture"], answer: "a" },
    { q: "IV administration is a safe route for giving iron.", options: ["True", "False"], answer: "True" },
    { q: "IM administration of iron causes some local pain and possibly staining the skin.", options: ["True", "False"], answer: "True" },
    { q: "Balanced suspension traction supports the affected extremity off the bed and allows for movement without disruption of pull.", options: ["True", "False"], answer: "True" },
    { q: "General complications of severe anemia EXCEPT:", options: ["A) Confusion", "B) Paresthesia", "C) Angina, heart failure", "D) Nephropathy"], answer: "d" },
    { q: "Crepitus is displacement or rotation of fracture fragments (either visible or palpable).", options: ["True", "False"], answer: "False" },
    { q: "Skin traction is used to control muscle spasms and to immobilize area before surgery.", options: ["True", "False"], answer: "True" },
    { q: "Hemodialysis patients should restrict protein.", options: ["True", "False"], answer: "False" },
    { q: "Erythropoietin deficiency causes:", options: ["A) Anemia", "B) Hypocalcemia", "C) Hypoglycemia", "D) All the above"], answer: "a" }
];


const mid2023Questions = [
    { q: "Which of the following symptoms DO NOT present in hyperglycemia?", options: ["A. Extreme thirst", "B. Hunger", "C. Blood glucose < 60 mg/dl", "D. Glycosuria"], answer: "c" },
    { q: "Type 1 diabetes typically have the following clinical characteristics:", options: ["A. Thin, young with ketones present in the urine", "B. Overweight, young", "C. Thin, older adult", "D. Overweight, older adult"], answer: "a" },
    { q: "Which of the following is normal range of fasting blood glucose level?", options: ["A. 70 - 100 mg/dl", "B. 60 - 120 mg/dl", "C. 110 - 130 mg/dl", "D. 140 - 180 mg/dl"], answer: "a" },
    { q: "State in which relatively normal blood glucose until about 3 AM then it begins to rise:", options: ["A. Somogyi Effect", "B. Dawn Phenomenon", "C. Insulin Waning", "D. Insulin resistance"], answer: "b" },
    { q: "What is a priority nursing assessment in the first 24 hours of a thrombotic stroke?", options: ["A. Cholesterol level", "B. Bowel sounds", "C. Pupil size and pupillary response", "D. Echocardiogram"], answer: "c" },
    { q: "What is the expected outcome of thrombolytic drug therapy?", options: ["A. Increased vascular permeability", "B. Prevention of emboli", "C. Dissolved emboli", "D. Decreased inflammation"], answer: "c" },
    { q: "Which assessment data indicates a risk for hemorrhagic stroke?", options: ["A. A blood pressure of 220/120 mmHg", "B. A blood glucose level of 110 mg/dl", "C. A high cholesterol level", "D. Presence of bronchogenic carcinoma"], answer: "a" },
    { q: "The physician orders mannitol for which of the following reasons?", options: ["A. To reduce intraocular pressure", "B. To promote osmotic diuresis to decrease ICP", "C. To prevent acute tubular necrosis", "D. To increase blood pressure"], answer: "b" },
    { q: "Autoimmune disorder where antibodies stimulate thyroid to produce too much T4:", options: ["A. Hyperthyroidism", "B. Graves' disease", "C. Hashimoto's thyroiditis", "D. Thyroid Storm"], answer: "b" },
    { q: "Which findings would the nurse elicit during a hypothyroidism assessment?", options: ["A. Elevated BP and tachycardia", "B. Increased appetite and weight loss", "C. Hypothermia and constipation", "D. Moist and flushed skin"], answer: "c" },
    { q: "A patient reports not eating enough iodine. He is most susceptible to:", options: ["A. Graves' disease", "B. Hypothyroidism", "C. Thyroid Storm", "D. Hyperthyroidism"], answer: "b" },
    { q: "Which represents a common clinical manifestation for iron deficiency anemia?", options: ["A. Jaundice", "B. Spoon-shaped nails", "C. Bruising", "D. Paresthesia"], answer: "b" },
    { q: "Intervention for 'activity intolerance' in a client with anemia:", options: ["A. Pace activities according to tolerance", "B. Provide supplements high in iron", "C. Administer packed red blood cells", "D. Monitor vital signs /4h"], answer: "a" },
    { q: "Which of the following can result in megaloblastic anemia?", options: ["A. Vitamin B-12 and folic acid", "B. Certain toxic materials", "C. Red cell destruction", "D. Infection"], answer: "a" },
    { q: "The nurse uses long-handled forceps when picking up any dislodged radioactive implant to:", options: ["A. Protect the nurse from radiation", "B. Protect the patient", "C. Maintain cleanness", "D. Prevent infection"], answer: "a" },
    { q: "Stage III in cancer staging (staging) means:", options: ["A. Limited local spread", "B. Extensive local and regional spread", "C. Cancer in situ", "D. Metastasis"], answer: "b" },
    { q: "A fracture where a fragment of bone is separated from the main mass by force of muscles:", options: ["A. Comminuted", "B. Compression", "C. Avulsion", "D. Spiral"], answer: "c" },
    { q: "Which assessment finding requires immediate notification for a client with a newly applied cast?", options: ["A. Moderate pain", "B. Slight edema", "C. Heat under cast", "D. Paresthesia in the toes"], answer: "d" },
    { q: "Carcinogenesis means:", options: ["A. Last stage of cancer", "B. Metastasis", "C. First stage of cancer", "D. Normal cell became cancer cell"], answer: "d" },
    { q: "Types of therapies delivered before the main treatment to reduce tumor size:", options: ["A. Complementary", "B. Targeted", "C. Neoadjuvant", "D. Adjuvant"], answer: "c" }
];


const previousQuizzesQuestions = [   
    { q: "While caring for a client with a newly applied cast, the nurse makes note of all the following conditions. Which assessment finding requires immediate notification of the physician?", options: ["Moderate pain, as reported by the client", "Presence of slight edema of the toes of the casted foot", "Report, by client, the heat is being felt under cast", "Paresthesia in the toes of the casted foot"], answer: "d" },
    { q: "While caring for a client with a newly applied cast, the nurse makes note of all the following: pain on passive stretch, motor loss, sensory loss, coolness, paleness. These findings indicate...", options: ["Pressure Ulcers", "Pneumonia", "Compartment Syndrome", "Disuse Syndrome"], answer: "c" },
    { q: "Expected outcome of cast application that the nurse evaluates is:", options: ["Tingling and numbness distal to the cast", "Skin irritation at the cast edges", "Decreased capillary refill and pallor", "Tingling and numbness distal to the cast"], answer: "c" },
    { q: "A fracture where a fragment of bone is separated from the main mass usually by force of muscles and tendons:", options: ["Comminuted Fracture", "Compression fracture", "Avulsion fracture", "Spiral Fracture"], answer: "c" },
    { q: "According to extend of disease classification (staging) of tumor, stage III means:", options: ["Limited local spread", "Extensive local and regional spread", "Cancer in situ", "Metastasis"], answer: "b" },
    { q: "The nurse uses long-handled forceps when picking up any dislodged radioactive implant, what is the purpose of this action?", options: ["to protect the nurse from radiation", "To protect the patients from injury of him", "To maintain cleanness of the hospital environment", "To prevent cross of infection"], answer: "a" },
    { q: "Is a type of treatment of cancer in which a diverse medical and health care systems, practices, and products that are not presently considered to be part of conventional medicine.", options: ["Radiotherapy", "Gene", "Complementary therapy", "Chemotherapy"], answer: "c" },
    { q: "Which of the following stages of cancer development where there is transformed cancer or malignant tumor experiences morphological changes in size.", options: ["Initiation", "Regression", "Promotion", "Progression"], answer: "d" },
    { q: "Insulin is the first line of treatment for newly diagnosed Type 2 diabetics.", options: ["True", "False"], answer: "False" },
    { q: "Type 2 diabetes is characterized by destruction of the pancreatic beta cells.", options: ["True", "False"], answer: "False" },
    { q: "Aplastic anemia is caused by deficiencies of vitamin B12 or folic acid.", options: ["True", "False"], answer: "False" },
    { q: "General complications of severe anemia include angina and heart failure.", options: ["True", "False"], answer: "True" },
    { q: "In iron deficiency anemia Jaundice is characteristic and is usually obvious in the sclerae.", options: ["True", "False"], answer: "False" },
    { q: "Diabetic Ketoacidosis occurs when the blood glucose falls to less than 50 to 60 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Bleeding is the most common cause of iron deficiency anemia in men and postmenopausal women.", options: ["True", "False"], answer: "True" },
    { q: "Glycated Hemoglobin is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 months.", options: ["True", "False"], answer: "True" },
    { q: "Crave ice or dirt may occur in Megaloblastic anemia.", options: ["True", "False"], answer: "False" },
    { q: "In patient with Diabetes Mellitus, Postprandial glucose test is equal or greater than 200 mg/dL.", options: ["True", "False"], answer: "True" },
    { q: "A female client arrives in emergency department with hand swelling and sever hand pain after falling on her hand, what is the first action should nurse to do?", options: ["tacks the patient to radiology department for x-ray", "give analgesic according to doctor order", "elevates the affected arm above the level of the heart.", "removes any tight clothes and jewelry from affected arm"], answer: "d" },
    { q: "What is the type of fracture that bone is fragmented into more than two bone fragments?", options: ["Comminuted fracture", "Impacted fracture", "Compound fracture", "complete fracture"], answer: "a" },
    { q: "The nursing purpose of use the needles with Luer-lock connection during giving chemotherapy is to:", options: ["Protect the patient skin from irritation.", "Prevent spread of infection.", "Provide accurate dose of chemotherapy", "Avoid accident disconnection of medication"], answer: "d" },
    { q: "Mr. Mohmed has above knee cast the nurse instruct the patient to practice isometric exercises, what is the purpose of this action?", options: ["To minimize disuse syndrome", "To decrease level of edema", "To improve joint movement", "all the above"], answer: "a" },
    { q: "Mr. Ahmed admitted to orthopedic department with hip fracture, the doctor applies skin traction as a temporary treatment. The nurse should assess the neurovascular status in the immediate period after traction application every:", options: ["every two hours", "30-60 minutes", "every 4 hours", "15-30 minutes"], answer: "d" },
    { q: "Types of therapies that delivered before the main treatment, to help reduce the size of a tumor or destroy cancer cells:", options: ["Complementary therapy", "Targeted Therapies", "Neoadjuvant therapies", "Adjuvant therapies"], answer: "d" },
    { q: "Carcinogenesis means:", options: ["Last stage of cancer development", "Development of cell metastasis", "First stage of cancer development", "Normal cell became cancer cell"], answer: "d" },
    { q: "Which of the following is example of delayed complications of fracture?", options: ["Shock", "Fat embolism", "Compartment syndrome", "Vascular necrosis of the bone"], answer: "d" },
    { q: "Which of the following stages of cancer development that involves alteration, change, or mutation of the genes:", options: ["Promotion.", "Progression.", "Initiation.", "Regression."], answer: "c" },
    { q: "Skull x-ray is the first diagnostic procedure done for confirmation of cerebro-vascular stroke.", options: ["True", "False"], answer: "False" },
    { q: "Time of onset of current stroke is important issue related to administration of tissue plasminogen activator (t-PA) medication.", options: ["True", "False"], answer: "True" },
    { q: "Nurse should assess conscious level for patient recently diagnosed with stroke.", options: ["True", "False"], answer: "True" },
    { q: "According to medical management of stroke, the thrombolytic drugs used for prevention of hemorrhage.", options: ["True", "False"], answer: "False" },
    { q: "Patient age is considered a modifiable risk factor for cerebro-vascular stroke occurrence.", options: ["True", "False"], answer: "False" },
    { q: "Simple fracture is a broken bone with an open wound on the fracture site, with or without bone protruding through it.", options: ["True", "False"], answer: "False" },
    { q: "Delayed complications include shock and compartment syndrome.", options: ["True", "False"], answer: "False" },
    { q: "Clinical Manifestations of fracture include Crepitus which is caused by the rubbing of the bone fragments against each other.", options: ["True", "False"], answer: "True" },
    { q: "Frequent assessment of neurovascular status distal to the injury should be assessed before and after splinting to determine the adequacy of peripheral tissue perfusion and nerve function.", options: ["True", "False"], answer: "True" },
    { q: "Open reduction refers to bringing the bone fragments into apposition through manipulation and manual traction.", options: ["True", "False"], answer: "False" },
    { q: "Gestational diabetes is diabetes diagnosed for the first time during pregnancy.", options: ["True", "False"], answer: "True" },
    { q: "Criteria for the Diagnosis of Diabetes Mellitus includes two-hour postprandial glucose ≥ 126 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Polydipsia refers to increased thirst.", options: ["True", "False"], answer: "True" },
    { q: "Diabetic Ketoacidosis is caused by an absence or markedly inadequate amount of insulin.", options: ["True", "False"], answer: "True" },
    { q: "Type 2 diabetes is characterized by destruction of the pancreatic beta cells.", options: ["True", "False"], answer: "False" },
    { q: "An increased appetite and progressive weight loss are common in hypothyroidism.", options: ["True", "False"], answer: "False" },
    { q: "In patient with Diabetes Mellitus, Postprandial glucose test is equal or greater than 200 mg/dL.", options: ["True", "False"], answer: "True" },
    { q: "Hashimoto's thyroiditis is the most common cause for of hyperthyroidism.", options: ["True", "False"], answer: "False" },
    { q: "Cold intolerance is common in hypothyroidism.", options: ["True", "False"], answer: "True" },
    { q: "Methimazole and propylthiouracil medications are used to treat hypothyroidism.", options: ["True", "False"], answer: "False" },
    { q: "Radioactive iodine is contraindicated during pregnancy.", options: ["True", "False"], answer: "True" },
    { q: "Glycated Hemoglobin is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 months.", options: ["True", "False"], answer: "True" },
    { q: "Insulin is the first line of treatment for newly diagnosed Type 2 diabetics.", options: ["True", "False"], answer: "False" },
    { q: "Type 2 diabetes is characterized by destruction of the pancreatic beta cells.", options: ["True", "False"], answer: "False" },
    { q: "Diabetic Ketoacidosis occurs when the blood glucose falls to less than 50 to 60 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Menorrhagia is the most common causes of iron deficiency anemia in premenopausal women.", options: ["True", "False"], answer: "True" },
    { q: "Iron deficiency anemia is a severe hemolytic anemia that results from inheritance of the gene causes the hemoglobin molecule to be defective.", options: ["True", "False"], answer: "False" },
    { q: "Bone marrow transplant may be used in management of aplastic anemia.", options: ["True", "False"], answer: "True" },
    { q: "Fat embolism is an area of the body that covered with muscle fibers occurs when pressure on this area increase causing poor blood supply in area distal to affected area.", options: ["True", "False"], answer: "False" },
    { q: "General care of patient with fractures elevating the injured extremity and applying ice as prescribed (ice in first 24 hours only).", options: ["True", "False"], answer: "True" },
    { q: "Patients with Sickle cell anemia are vulnerable to problems related to erythrocyte, leukocyte, and platelet deficiencies.", options: ["True", "False"], answer: "False" },
    { q: "Use a strict aseptic technique in dressing for patients with closed fractures.", options: ["True", "False"], answer: "False" },
    { q: "Deep vein thrombosis, a serious circulatory impairment of skin traction, may be manifested by unilateral calf tenderness, warmth, redness, and swelling.", options: ["True", "False"], answer: "True" },
    { q: "In iron deficiency anemia Jaundice is characteristic and is usually obvious in the sclerae.", options: ["True", "False"], answer: "False" },
    { q: "Skin traction is used to control muscle spasms and to immobilize an area before surgery.", options: ["True", "False"], answer: "True" },
    { q: "Lipohypertrophy is the development of fibrofatty masses at the insulin injection site, is caused by the repeated use of an injection site.", options: ["True", "False"], answer: "True" },
    { q: "Iron deficiency anemia is a severe hemolytic anemia that results from inheritance of the gene causes the hemoglobin molecule to be defective.", options: ["True", "False"], answer: "False" },
    { q: "Hashimoto's thyroiditis is the most common cause for of hyperthyroidism.", options: ["True", "False"], answer: "False" },
    { q: "Clinical manifestations of Myxedema coma/crisis include High fever and extreme tachycardia.", options: ["True", "False"], answer: "False" },
    { q: "Diabetic Ketoacidosis occurs when the blood glucose falls to less than 50 to 60 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Deficiency of erythropoietin can represent a cause for aplastic anemia.", options: ["True", "False"], answer: "False" },
    { q: "In Hypoglycemia; blood glucose levels may vary between 300 - 800 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Beta-blocker agents can be used as an adjunctive therapy for hyperthyroidism.", options: ["True", "False"], answer: "True" },
    { q: "Bone marrow transplant may be used in management of aplastic anemia.", options: ["True", "False"], answer: "True" },
    { q: "Radioactive iodine is contraindicated during pregnancy.", options: ["True", "False"], answer: "True" },

    // الأسئلة من الصور الجديدة (التي كانت في التطبيق/الموقع)
    { q: "Compartment syndrome is a one of delayed complications of fracture.", options: ["True", "False"], answer: "False" },
    { q: "Closed Fracture refers to broken bone with an open wound on the fracture site, with or without bone protruding through it.", options: ["True", "False"], answer: "False" },
    { q: "During closed reduction the orthopedic surgeon may be used plates, & metallic pins to hold the bone fragments in position.", options: ["True", "False"], answer: "False" },
    { q: "The presence of thrill (vibration) in the site of arteriovenous fistula site indicates major complication.", options: ["True", "False"], answer: "False" },
    { q: "An arteriovenous fistula is a surgical anastomosis (connection) of an artery and vein lying in close proximity.", options: ["True", "False"], answer: "True" },
    { q: "Azotemia, means accumulation nitrogenous wastes such as creatinine and uric acid in the blood.", options: ["True", "False"], answer: "True" },
    { q: "stages 3 of chronic renal disease include Severe decrease in kidney function with GFR of 15-29.", options: ["True", "False"], answer: "False" },
    { q: "The nurse should maintain effective traction by assuring the prescribed weight is hanging free.", options: ["True", "False"], answer: "True" },
    { q: "Acute renal failure is characterized by progressive and irreversible damage to the nephrons.", options: ["True", "False"], answer: "False" },
    { q: "Buck's extension traction is an example of balanced suspension traction.", options: ["True", "False"], answer: "True" },
    { q: "Ketones is a signal that there is a deficiency of insulin and control of type 1 diabetes is deteriorating.", options: ["True", "False"], answer: "True" },
    { q: "Beta-blocker agents are important in controlling the sympathetic nervous system effects of hyperthyroidism.", options: ["True", "False"], answer: "True" },
    { q: "Hashimoto's thyroiditis is the most common cause for of hyperthyroidism.", options: ["True", "False"], answer: "False" },
    { q: "Cold intolerance is common in hypothyroidism.", options: ["True", "False"], answer: "True" },
    { q: "An increased appetite and dietary intake and progressive weight loss are common in hypothyroidism.", options: ["True", "False"], answer: "False" },
    { q: "Glycated Hemoglobin Is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 weeks.", options: ["True", "False"], answer: "False" },
    { q: "Type 2 diabetes Is characterized by destruction of the pancreatic beta cells.", options: ["True", "False"], answer: "False" },
    { q: "Methimazole & propylthiouracil medications are used to treat hyperthyroidism.", options: ["True", "False"], answer: "True" },
    { q: "Management of hypoglycemia include blood glucose retested in 5 minutes and retreated if it is less than 100 to 110 mg/dL.", options: ["True", "False"], answer: "False" },
    { q: "Initial infusion for management of Diabetic Ketoacidosis includes dextrose 5% in water solution is administered at a rapid rate, usually 0.5 to 1 L/h for 2 to 3 hours.", options: ["True", "False"], answer: "False" }
];
    



// المصفوفات الفاضية اللي طلبتيها عشان تضيفي فيها براحتك
const finalSummer2024Questions = [
  { q: "A patient screened for diabetes at a clinic has a fasting plasma glucose level of 120 mg/dl. The nurse will plan to teach the patient about:", 
    options: ["A) Use of low doses of regular insulin.", "B) Self-monitoring of blood glucose.", "C) Oral hypoglycemic medications.", "D) Maintenance of a healthy weight."], 
    answer: "b" 
  }, 
  { 
    q: "The nurse's first action upon finding a patient with mild hypoglycemia is to:", 
const summerExamQuestions = [
  // --- Multiple Choice Questions (1 - 54) ---
  { 
    q: "A patient screened for diabetes at a clinic has a fasting plasma glucose level of 120 mg/dl. The nurse will plan to teach the patient about:", 
    options: ["A) Use of low doses of regular insulin.", "B) Self-monitoring of blood glucose.", "C) Oral hypoglycemic medications.", "D) Maintenance of a healthy weight."], 
    answer: "b" 
  }, 
  { 
    q: "The nurse's first action upon finding a patient with mild hypoglycemia is to:", 
    options: ["A) Give a protein snack", "B) Give 1 mg of glucagon", "C) Give carbohydrate or juice", "D) Give insulin"], 
    answer: "c" 
  },
  { 
    q: "The nurse is preparing patients newly diagnosed with diabetes mellitus (DM) for discharge from hospital. What should the nurse include in patient teaching regarding medications to treat DM?", 
    options: ["A) Patients with type 1 diabetes may achieve normal blood glucose levels with oral medications.", "B) Type 1 diabetes may progress to type 2 if blood glucose levels are not well controlled.", "C) Patients with type 1 diabetes will always need an exogenous source of insulin.", "D) Patients with type 2 diabetes generally need a combination of oral medications and insulin to achieve normal blood glucose levels."], 
    answer: "c" 
  },
  { 
    q: "___ is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 months.", 
    options: ["A) Fasting plasma glucose", "B) Random (casual) plasma glucose", "C) Glycosylated hemoglobin", "D) Two-hour postprandial glucose"], 
    answer: "c" 
  },
  { 
    q: "A client with a diagnosis of type 1 diabetes mellitus had vomiting and diarrhea and tells the nurse that no food has been consumed for the last 24 hours. Which additional statement by the client indicates a need for teaching?", 
    options: ["A) 'I need to stop my insulin.'", "B) 'I need to increase my fluid intake.'", "C) 'I need to monitor my blood glucose every 3 to 4 hours.'", "D) 'I need to call the physician because of these symptoms.'"], 
    answer: "a" 
  },
  { 
    q: "A 25-year-old male patient who has type 1 diabetes normally walks each evening as part of an exercise regimen. He now plans to take a swimming class every day at 1:00 PM. The clinic nurse teaches the patient to:", 
    options: ["A) Delay eating the noon meal until after the swimming class.", "B) Increase the morning dose of insulin on days of the swimming class.", "C) Check glucose level before, during, and after swimming.", "D) Avoid taking snacks at the end of the swimming class."], 
    answer: "c" 
  },
  { 
    q: "___ is characterized by insufficient secretion of insulin from the β-cells of the pancreatic islets, coupled with insulin resistance.", 
    options: ["A) Type 2 diabetes", "B) Gestational diabetes", "C) Type 1 Diabetes", "D) Prediabetes"], 
    answer: "a" 
  },
  { 
    q: "All the following signs and symptoms of patient with hyperthyroidism are common EXCEPT?", 
    options: ["A) Weight loss", "B) Palpitations", "C) Intolerance to heat", "D) Weight gain"], 
    answer: "d" 
  },
  { 
    q: "___ is an autoimmune disorder in which antibodies produced by the immune system stimulate the thyroid to produce too much T4.", 
    options: ["A) Hyperthyroidism", "B) Graves' disease", "C) Hashimoto's thyroiditis", "D) Thyroid Storm"], 
    answer: "b" 
  },
  { 
    q: "A patient admitted with spoon-shaped nails. Which type of anemia would the nurse suspect the client has developed?", 
    options: ["A) Iron deficiency anemia", "B) Megaloblastic anemia", "C) Aplastic anemia", "D) Hemolytic Anemia"], 
    answer: "a" 
  },
  { 
    q: "The nurse is caring for a client who is thought to have sickle cell anemia. What signs and symptoms would the nurse expect in this person?", 
    options: ["A) Paresthesia", "B) Spoon-shaped nails", "C) Jaundice", "D) Brittle nails"], 
    answer: "c" 
  },
  { 
    q: "All of the following can occur as a complication of severe anemia EXCEPT?", 
    options: ["A) Heart failure", "B) Nephropathy", "C) Paresthesia", "D) Confusion"], 
    answer: "b" 
  },
  { 
    q: "___ is a rare disease caused by a decrease in or damage to marrow stem cells resulting in bone marrow aplasia.", 
    options: ["A) Iron deficiency anemia", "B) Megaloblastic anemia", "C) Aplastic anemia", "D) Hemolytic Anemia"], 
    answer: "c" 
  },
  { 
    q: "The nurse is caring for a client who is thought to have iron deficiency anemia. What signs and symptoms would the nurse expect in this person?", 
    options: ["A) Signs of infection and bleeding", "B) Craving for ice or dirt", "C) Numbness and tingling in the feet and lower legs", "D) Jaundice and is usually obvious in the sclera"], 
    answer: "b" 
  },
  { 
    q: "A female client who receives a diagnosis of pernicious anemia asks why she must receive vitamin injections. What is the best answer for the nurse to give?", 
    options: ["A) 'Injections work faster than pills.'", "B) 'Your body cannot absorb vitamin B12 from foods.'", "C) 'Vitamins are necessary to make the blood cells.'", "D) 'You can get more vitamins in an injection than a pill.'"], 
    answer: "b" 
  },
  { 
    q: "Which of the following can represent a cause for aplastic anemia?", 
    options: ["A) Absence of intrinsic factor", "B) A deficiency of erythropoietin", "C) Chemotherapy treatment", "D) Lack of iron in diet"], 
    answer: "c" 
  },
  { 
    q: "___ typically results when the intake of dietary iron is inadequate for hemoglobin synthesis.", 
    options: ["A) Iron deficiency anemia", "B) Megaloblastic anemias", "C) Aplastic anemia", "D) Hemolytic Anemias"], 
    answer: "a" 
  },
  { 
    q: "An expected outcome of cast application that the nurse evaluates is:", 
    options: ["A) Skin irritation at the cast edges", "B) Decreased capillary refill and pallor", "C) Tingling and numbness distal to the cast", "D) Slight edema, soreness, and limitation of range of motion"], 
    answer: "d" 
  },
  { 
    q: "___ usually occurs in the vertebrae, is a collapse of a vertebra due to osteoporosis or trauma.", 
    options: ["A) Spiral Fracture", "B) Comminuted Fracture", "C) Compression fracture", "D) Avulsion fracture"], 
    answer: "c" 
  },
  { 
    q: "When taking a health history, the nurse screens for manifestations suggestive of diabetes type I. Which of the following manifestations is suggestive of diabetes type I and require follow-up investigations?", 
    options: ["A) Excessive intake of calories", "B) Poor circulation", "C) Lack of energy", "D) An increase in thirst, hunger and frequent, high-volume urination"], 
    answer: "d" 
  },
  { 
    q: "___ is an eye condition that can cause vision loss and blindness in people who have diabetes.", 
    options: ["A) Peripheral neuropathy", "B) Diabetic retinopathy", "C) Nephropathy", "D) Myocardial infarction"], 
    answer: "b" 
  },
  { 
    q: "Which of the following represent a cause of hypoglycemia?", 
    options: ["A) Decreased dose of insulin", "B) Illness or infection", "C) Untreated diabetes", "D) Explicitly high or excessive physical activity"], 
    answer: "d" 
  },
  { 
    q: "___ is caused by an absence or markedly inadequate amount of insulin.", 
    options: ["A) Diabetic Ketoacidosis", "B) Hypoglycemia", "C) Gestational diabetes", "D) Prediabetes"], 
    answer: "a" 
  },
  { 
    q: "Which of the following statements are true regarding Type 2 diabetes medications?", 
    options: ["A) Insulin and oral meds routinely used", "B) Oral meds during surgery only", "C) Insulin is never taken", "D) Oral diabetic medications used for treatment of Type 2 diabetes."], 
    answer: "d" 
  },
  { 
    q: "___ is the major electrolyte of concern during treatment of diabetic ketoacidosis.", 
    options: ["A) Sodium", "B) Potassium", "C) Magnesium", "D) Calcium"], 
    answer: "b" 
  },
  { 
    q: "Which nursing intervention should be included in the plan of care for the client diagnosed with hyperthyroidism?", 
    options: ["A) Increase fiber", "B) Low-calorie diet", "C) Decrease fluid", "D) Provide six (6) small, well-balanced meals a day."], 
    answer: "d" 
  },
  { 
    q: "A patient reports that he does not eat enough iodine in his diet. What condition is he most susceptible to?", 
    options: ["A) Graves' disease", "B) Thyroid Storm", "C) Hyperthyroidism", "D) Hypothyroidism"], 
    answer: "d" 
  },
  { 
    q: "A patient was recently discharged home for treatment of hypothyroidism. The patient is re-admitted with hypothermia and drowsiness. Which of the following conditions is this?", 
    options: ["A) Thyroid Storm", "B) Myxedema Coma", "C) Iodism", "D) Toxic Nodular Goiter"], 
    answer: "b" 
  },
  { 
    q: "Which nursing care measure is essential because a client has exophthalmos?", 
    options: ["A) Administer artificial tears.", "B) Wear glasses.", "C) Monitor pulse.", "D) Promote bed rest."], 
    answer: "a" 
  },
  { 
    q: "All the following represent medical treatment for hyperthyroidism EXCEPT:", 
    options: ["A) Beta-blocker", "B) Synthetic levothyroxine", "C) Radioactive Iodine", "D) Propylthiouracil"], 
    answer: "b" 
  },
  { 
    q: "Fat embolism is a complication of fracture which is common in:", 
    options: ["A) Hand bone", "B) Vertebral bone", "C) Femur bone fracture", "D) Skull bone"], 
    answer: "c" 
  },
  { 
    q: "Which assessment finding requires immediate notification of the physician after cast application?", 
    options: ["A) Moderate pain", "B) Heat felt under cast", "C) Slight edema", "D) Paresthesia in the toes of the casted foot"], 
    answer: "d" 
  },
  { 
    q: "All the following are clinical manifestations of fracture EXCEPT:", 
    options: ["A) Generalized edema", "B) Loss of function", "C) Shortening", "D) Pain"], 
    answer: "a" 
  },
  { 
    q: "After cast application the nurse should assess circulation, sensation, and mobility every:", 
    options: ["A) 24 hours", "B) 1- to 2 hours", "C) 6 hours", "D) 12 hours"], 
    answer: "b" 
  },
  { 
    q: "Which statement best describes closed reduction?", 
    options: ["A) Surgical exposure", "B) Hospitalization", "C) It uses manual manipulation and traction without surgery", "D) Inserting screws"], 
    answer: "c" 
  },
  { 
    q: "The purpose of administering Erythropoietin hormone for a patient with chronic renal failure:", 
    options: ["A) Treatment of anemia", "B) Decrease creatinine", "C) Reduce hypercalcemia", "D) Prevent blood clot"], 
    answer: "a" 
  },
  { 
    q: "Which of the following is the most accurate way to monitor kidney function in CKD?", 
    options: ["A) Intake/Output", "B) Urine gravity", "C) Check BUN & serum creatinine level", "D) X-ray"], 
    answer: "c" 
  },
  { 
    q: "Immunosuppressive drugs are taken with:", 
    options: ["A) Hemodialysis", "B) Peritoneal dialysis", "C) Kidney transplant", "D) Major viruses"], 
    answer: "c" 
  },
  { 
    q: "___ is an abnormal connection between an artery and a vein created for hemodialysis.", 
    options: ["A) Arteriovenous fistula", "B) Peritoneal dialysis", "C) Hemodialysis", "D) Diuresis"], 
    answer: "a" 
  },
  { 
    q: "How often must hemodialysis usually be done?", 
    options: ["A) Every day", "B) Twice", "C) Once", "D) 3 times a week"], 
    answer: "d" 
  },
  { 
    q: "In peritoneal dialysis, which part of the body acts as a filter?", 
    options: ["A) Lining of stomach", "B) The lining of the abdomen", "C) Intestines", "D) Lungs"], 
    answer: "b" 
  },
  { 
    q: "What is the most important nursing diagnosis for ESRD?", 
    options: ["A) Risk for injury", "B) Fluid volume excess", "C) Activity intolerance", "D) Altered nutrition"], 
    answer: "b" 
  },
  { 
    q: "According to staging of tumor, stage IV means:", 
    options: ["A) Cancer in situ", "B) Metastasis", "C) Limited local spread", "D) Extensive local spread"], 
    answer: "b" 
  },
  { 
    q: "Carcinomas means:", 
    options: ["A) Growing of epithelial cells & usually solid tumors", "B) Lymphoid tissue", "C) Muscle/bone", "D) Tissue of origin"], 
    answer: "a" 
  },
  { 
    q: "Which of the following skin lesions should be reported immediately?", 
    options: ["A) Small mole", "B) Birthmark", "C) Small warts", "D) A black and purple mole that is growing larger and has a different shape"], 
    answer: "d" 
  },
  { 
    q: "All the following are risk factors of osteoarthritis EXCEPT:", 
    options: ["A) Older age", "B) Obesity", "C) Female gender", "D) Young age"], 
    answer: "d" 
  },
  { 
    q: "Crepitus is common in which of the following?", 
    options: ["A) Fracture", "B) Osteoarthritis", "C) Rheumatoid arthritis", "D) All of the above"], 
    answer: "d" 
  },
  { 
    q: "Purpose of using assistive devices like canes for RA:", 
    options: ["A) To reduce the amount of weight bearing on the joints", "B) Correct walk", "C) Prevent falling", "D) Strengthen muscles"], 
    answer: "a" 
  },
  { 
    q: "Arthroplasty is:", 
    options: ["A) Excision of synovial membrane", "B) Fusion of joint", "C) Suturing", "D) Surgical replacement of the joint"], 
    answer: "d" 
  },
  { 
    q: "Rheumatoid Arthritis is primarily classified as:", 
    options: ["A) Infectious", "B) Autoimmune disease", "C) Degenerative", "D) Genetic"], 
    answer: "b" 
  },
  { 
    q: "What is the primary goal of treating RA?", 
    options: ["A) Cure", "B) Increase inflammation", "C) To decrease pain, reduce swelling, and prevent joint deformity", "D) Increase activity"], 
    answer: "c" 
  },
  { 
    q: "Which layer of skin is primarily affected in superficial partial-thickness burns?", 
    options: ["A) Dermis", "B) Epidermis", "C) Subcutaneous"], 
    answer: "b" 
  },
  { 
    q: "Lumbar puncture is contraindicated in patients with subarachnoid hemorrhage because:", 
    options: ["A) Vomiting", "B) Intracranial pressure (ICP) is increased.", "C) Ventilation", "D) CSF blood"], 
    answer: "b" 
  },
  { 
    q: "Which of the following values is considered normal for ICP?", 
    options: ["A) 10 to 20 mm Hg", "B) 35 to 45 mm Hg", "C) 25 mm Hg", "D) 120/80 mm Hg"], 
    answer: "a" 
  },

  // --- True / False Section (55 - 70) ---
  { q: "The initial clinical manifestations of rheumatoid arthritis include symmetric joint pain and morning joint stiffness lasting longer than 1 hour.", options: ["True", "False"], answer: "True" },
  { q: "In osteoarthritis, the affected joint may be enlarged with a decreased range of motion.", options: ["True", "False"], answer: "True" },
  { q: "Etiology of elevated intracranial pressure includes tumors and aneurysm.", options: ["True", "False"], answer: "True" },
  { q: "Hemorrhagic stroke is the most common type of stroke.", options: ["True", "False"], answer: "False" },
  { q: "Hypertension is the primary risk factor for stroke.", options: ["True", "False"], answer: "True" },
  { q: "Heat intolerance is one of clinical manifestations of hypothyroidism.", options: ["True", "False"], answer: "False" },
  { q: "Hashimoto's thyroiditis is the most common cause of hyperthyroidism.", options: ["True", "False"], answer: "False" },
  { q: "Closed fracture refers to a broken bone with an open wound on the fracture site.", options: ["True", "False"], answer: "False" },
  { q: "After cast application, the nurse should handle the wet cast with the palms of the hand.", options: ["True", "False"], answer: "True" },
  { q: "Nursing interventions for hemodialysis include protein restriction.", options: ["True", "False"], answer: "True" },
  { q: "Patient's weight should be assessed in pre- and post-dialysis care.", options: ["True", "False"], answer: "True" },
  { q: "In megaloblastic anemias, the erythrocytes that are produced are abnormally large.", options: ["True", "False"], answer: "True" },
  { q: "A deficiency of erythropoietin can represent a cause for sickle cell anemia.", options: ["True", "False"], answer: "False" },
  { q: "In hypoglycemia, blood glucose levels may vary between 300-800 mg/dL.", options: ["True", "False"], answer: "False" },
  { q: "For diagnosis of diabetes mellitus, postprandial glucose test is equal or greater than 200 mg/dL.", options: ["True", "False"], answer: "True" },
  { q: "Clinical manifestations of diabetic ketoacidosis include: sweating, nervousness, and hunger.", options: ["True", "False"], answer: "False" }
];
              


    const final2024Questions = [
  { q: "After cast application the nurse should assess the circulation, sensation, and mobility of the affected part every:", options: ["every 6 hours", "every 24 hours", "every 12 hours", "1 to 2 hours"], answer: "1 to 2 hours" },
  { q: "In fracture, deformity means:", options: ["Immobility of the fractured part", "Abnormal position, of the fractured part", "Increase the pain level", "abnormal sensation of the fractured part"], answer: "Abnormal position, of the fractured part" },
  { q: "All the following are clinical manifestation of fracture Except:", options: ["Generalized edema", "Loss of function", "Shortening of the extremity", "Pain"], answer: "Generalized edema" },
  { q: "The nurse instructs the patient with lower limb cast to simply exercises for affected part by contraction and relaxation of the muscles without pink movement. What is the type of this exercises?", options: ["isotonic exercises", "Range of Motion exercises", "isometric exercises", "all of the above"], answer: "isometric exercises" },
  { q: "What is the purpose of skin traction?", options: ["Increases the muscle strength", "Prompt good healing of fracture", "Immobilize fracture part", "all of the above"], answer: "Immobilize fracture part" },
  { q: "Crepitus is one of clinical manifestation of fracture, which of the following true about crepitus?", options: ["It caused by the rubbing of bone fragments against each other.", "It occurred due to contraction of the muscle.", "It occurred due to compression of the nerve.", "It occurred due to rupture of small blood vessels."], answer: "It caused by the rubbing of bone fragments against each other." },
  { q: "Which of the following is a one of delayed complications of fracture?", options: ["Shock", "Compartment syndrome", "Malunion", "Fat embolism"], answer: "Malunion" },
  { q: "Mr. Ahmed came to the outpatient clinic for follow-up of an external fixation device in the left lower limb. What is the important point that the nurse should assess?", options: ["Pin site infection", "Ability of bearing down on his limb", "Healing process of the fracture", "The nutritional status"], answer: "Pin site infection" },
  { q: "Which of the following is a characteristic of benign tumors?", options: ["Invasive growth", "Presence of metastasis", "Immature, poorly differentiated tissue", "Resembles to normal cells."], answer: "Resembles to normal cells." },
  { q: "Miss Mona admitted to oncology department suffer from left side breast cancer. The doctor prescribes initial dose of radiotherapy and after complete of 6 doses miss Mona will perform radical mastectomy, what is the type of this radiotherapy?", options: ["Neoadjuvant therapies", "Complementary therapy", "Adjuvant therapies", "Biological therapies"], answer: "Neoadjuvant therapies" },
  { q: "Which of the following is considered as one of early side effects of radiotherapy?", options: ["Radio-necrosis of the human cell", "Hypothalamus and pituitary abnormality", "Skin irritation", "Cognitive impairment"], answer: "Skin irritation" },
  { q: "Mr. Ahmed was diagnosed as acute leukemia. He planned for bone marrow transplantation from his father, what is the type of this bone marrow donor?", options: ["Autologous", "Synergic", "Allogenic", "Homologous"], answer: "Allogenic" },
  { q: "Types of therapies that delivered before the main treatment, to help reduce the size of a tumor or destroy cancer cells:", options: ["Neoadjuvant therapies", "Complementary therapy", "Adjuvant therapies", "Targeted Therapies"], answer: "Neoadjuvant therapies" },
  { q: "Chemotherapy has the greatest effect on rapidly dividing cells, such as those found in which of the following?", options: ["Bone marrow", "Hair follicles", "Mucous membranes", "All of the above"], answer: "All of the above" },
  { q: "The purpose of giving hormone therapy for cancer patients is.........", options: ["To improve immunity of the patients", "To prevent cancer cells from getting the hormones they need to grow", "To decrease the invasive of metastasis", "To improve effect of chemotherapy with minimal side effect"], answer: "To prevent cancer cells from getting the hormones they need to grow" },
  { q: "What is the appropriate nursing action if a chemotherapeutic drug touches skin?", options: ["Wash area with mild soap and water", "Clean the skin with normal saline", "Report to the doctor", "Dry the skin with sterile towel."], answer: "Wash area with mild soap and water" },
  { q: "All the following are risk factors of osteoarthritis Except which of the following:", options: ["Older age", "Female gender", "Obesity", "Young age"], answer: "Young age" },
  { q: "Crepitus is audible, grating sound felt in joint that common in which of the following?", options: ["Fracture", "Osteoarthritis", "Rheumatoid arthritis", "All of the above"], answer: "All of the above" },
  { q: "To improve self-care activities for patient with RA nurse advice patients to use Assistive devices as canes or walkers, what is the purpose of this nursing action?", options: ["To reduce the amount of weight bearing on the joints", "To restoring joint mobility & strengthening the muscles", "To prevent fall down", "To help in correct walk"], answer: "To reduce the amount of weight bearing on the joints" },
  { q: "Arthroplasty is a surgical procedure that can be performed for patient with rheumatoid arthritis which refers to.........", options: ["Excision of the synovial membrane", "Surgical fusion of the joint", "Suturing of a tendon", "Surgical replacement of the joint"], answer: "Surgical replacement of the joint" },
  { q: "Mrs. Amany is suffering from osteoarthritis with her knee joint, what is the aim of the physician injected gel-like substances into her knee joint, what is the aim of this action?", options: ["To prevent loss of cartilage", "To prevent deformity", "To reduce pain", "To reduce inflammation"], answer: "To reduce pain" },
  { q: "To prevent kyphosis for patients with rheumatoid arthritis, the nurse should advise the patient to sleep in which of the following position?", options: ["Lie flat on a firm mattress with only one pillow under the head", "Lie flat on a soft mattress with one pillow under the head and lumbar area", "Fowler position", "Side lying position"], answer: "Lie flat on a firm mattress with only one pillow under the head" },
  { q: "When taking a health history, the nurse screens for manifestations suggestive of diabetes type 1. Which of the following manifestations are most suggestive of diabetes type 1 and require follow-up investigation?", options: ["Excessive intake of calories, rapid weight gain, and difficulty losing weight.", "Poor circulation, wound healing, and leg ulcers", "Lack of energy, weight gain, and depression", "An increase in thirst, hunger and Frequent, high-volume urination"], answer: "An increase in thirst, hunger and Frequent, high-volume urination" },
  { q: "The newly diagnosed diabetic patient asks the nurse why he needs to check his feet every day. The nurse's best response is:", options: ["To prevent leg amputation.", "To check for any cuts, sores, or dry cracked skin so they can be treated early to prevent infection or gangrene.", "To see if they hurt.", "You just need to do it."], answer: "To check for any cuts, sores, or dry cracked skin so they can be treated early to prevent infection or gangrene." },
  { q: "The nurse provides instructions to a client newly diagnosed with type 1 diabetes mellitus. The nurse recognizes accurate understanding of measures to prevent diabetic ketoacidosis when the client makes which statement?", options: ["I will stop taking my insulin if I'm too sick to eat", "I will decrease my insulin dose during times of illness", "I will test blood glucose levels and urine ketones once a day and keep a record", "I will notify physician if my blood glucose level is higher than 300 mg/dL."], answer: "I will notify physician if my blood glucose level is higher than 300 mg/dL." },
  { q: "During a diabetes screening program, a patient tells the nurse, 'My mother died of complications of type 2 diabetes, Can I inherit diabetes?' The nurse explains that:", options: ["As long as the patient maintains normal weight and exercises, type 2 diabetes can be prevented.", "The patient is at a higher-than-normal risk for type 2 diabetes and should have periodic blood glucose level testing.", "There is a greater risk for children developing type 2 diabetes when the father has type 2 diabetes.", "Although there is a tendency for children of people with type 2 diabetes to develop diabetes, the risk is higher for those with type 1 diabetes."], answer: "The patient is at a higher-than-normal risk for type 2 diabetes and should have periodic blood glucose level testing." },
  { q: "A 54-year-old patient admitted with type 2 diabetes asks the nurse what 'type 2' means. What is the most appropriate response by the nurse?", options: ["With type 2 diabetes, the body of the pancreas becomes inflamed", "With type 2 diabetes, insulin secretion is decreased, and insulin resistance is increased.", "With type 2 diabetes, the patient is totally dependent on an outside source of insulin", "With type 2 diabetes, the body produces autoantibodies that destroy B-cells in pancreas"], answer: "With type 2 diabetes, insulin secretion is decreased, and insulin resistance is increased." },
  { q: "A patient arrives at the emergency department with a blood glucose of 578, severe thirst, dehydration, and confusion. The patient is breathing rapidly and has a fruity breath smell. This patient has symptoms of:", options: ["Diabetic ketoacidosis", "Normal findings", "Hypoglycemia", "Diabetic neuropathy"], answer: "Diabetic ketoacidosis" },
  { q: "Is the major electrolyte of concern during treatment of diabetic ketoacidosis:", options: ["Sodium", "Potassium", "Magnesium", "Calcium"], answer: "Potassium" },
  { q: "Is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 months:", options: ["Fasting plasma glucose", "Random (casual) plasma glucose", "Glycosylated hemoglobin", "Two-hour postprandial glucose"], answer: "Glycosylated hemoglobin" },
  { q: "The development of fibrofatty masses at the injection site, is caused by the repeated use of an injection site:", options: ["Lipoatrophy", "local Allergic Reactions", "Lipohypertrophy", "Resistance to Injected Insulin"], answer: "Lipohypertrophy" },
  { q: "A patient screened for diabetes at a clinic has a fasting plasma glucose level of 120 mg/dl. The nurse will plan to teach the patient about:", options: ["Use of low doses of regular insulin.", "Self-monitoring of blood glucose.", "Oral hypoglycemic medications", "Maintenance of a healthy weight"], answer: "Self-monitoring of blood glucose." },
  { q: "Patient is admitted with iron-deficiency anemia & has been receiving iron supplementation. The patient concerns about how his stool is dark black. As the nurse, you would?", options: ["Notify the doctor", "Hold the next dose of iron", "Reassure the patient this is a normal side effect of iron supplementation", "None of the options are correct"], answer: "Reassure the patient this is a normal side effect of iron supplementation" },
  { q: "You're providing education to a patient about how to take their prescribed iron supplement. Which statement by the patient requires you to re-educate the patient on how to take this supplement?", options: ["I will take this medication on an empty stomach", "I will avoid taking this medication with orange juice", "I will avoid taking antacids", "This medication can cause constipation."], answer: "I will avoid taking this medication with orange juice" },
  { q: "The nurse writes a client problem of 'activity intolerance' for a client diagnosed with anemia. Which intervention should the nurse implement?", options: ["Pace activities according to tolerance", "Provide supplements high in iron & vitamins", "Administer packed red blood cells", "Monitor vital signs /4h"], answer: "Pace activities according to tolerance" },
  { q: "Which of the following can result in megaloblastic anemia?", options: ["Certain toxic materials", "Red cell destruction", "Vitamin B-12 and folic acid", "Infection"], answer: "Vitamin B-12 and folic acid" },
  { q: "A female client who receives a diagnosis of pernicious anemia asks why she must receive vitamin injections. What is the best answer for the nurse to give?", options: ["Injections work faster than pills", "Your body cannot absorb vitamin B12 from foods", "Vitamins are necessary to make the blood cells", "You can get more vitamins in an injection than a pill."], answer: "Your body cannot absorb vitamin B12 from foods" },
  { q: "A patient, with a history of Celiac Disease 6 months ago, reports feeling very fatigued and is having food cravings for clay and dirt. On assessment, you note that the patient has nail changes that look 'spoon-shaped'. Which type of anemia would the nurse suspect the patient has developed?", options: ["Iron deficiency anemia", "Aplastic anemia", "Vitamin B12 deficiency", "Sickle cell anemia"], answer: "Iron deficiency anemia" },
  { q: "Which of the following can represent a medical management for patient with anemia of chronic disease?", options: ["Treatment of the underlying disorder", "Iron supplementation", "Immunosuppressive therapy", "Bone marrow transplant"], answer: "Treatment of the underlying disorder" },
  { q: "Represents the most common cause hypothyroidism:", options: ["Radioactive iodine", "Hashimoto's thyroiditis", "Iodine deficiency", "Graves' disease"], answer: "Hashimoto's thyroiditis" },
  { q: "For patient with hyperthyroidism, which of following nursing care should be considered:", options: ["Provide foods high in fiber", "Monitor patient's body temperature", "The patient may need instructions about instillation of eye drops or ointment", "Encourage increased mobility"], answer: "The patient may need instructions about instillation of eye drops or ointment" },
  { q: "The client is diagnosed with hyperthyroidism All the following the nurse will expect the client to exhibit EXCEPT?", options: ["Complaints of extreme fatigue and nervousness", "Exophthalmos and nervousness", "Complaints of profuse sweating and flushed skin", "Increased appetite and weight loss"], answer: "Complaints of extreme fatigue and nervousness" },
  { q: "The nurse identifies client problem 'risk for imbalanced body temperature' for client diagnosed with hypothyroidism. Which intervention should be included in plan of care?", options: ["Discourage the use of an electric blanket", "Keep the room temperature cool", "Assess the client's temperature every (2) hours", "Space activities to promote rest"], answer: "Discourage the use of an electric blanket" },
  { q: "A patient is receiving radioactive iodine treatment for hyperthyroidism. What will you include in your patient education to this patient about this type of treatment?", options: ["Taste changes", "Constipation", "Excessive thirst", "Sun protection"], answer: "Taste changes" },
  { q: "Is the preferred preparation for treating hypothyroidism:", options: ["Beta-blocker agents", "Synthetic levothyroxine", "Radioactive iodine", "Propylthiouracil"], answer: "Synthetic levothyroxine" },
  { q: "The nurse is assessing a patient experiencing complete motor loss as a result of left side cerebrovascular stroke, which clinical manifestation would the nurse document?", options: ["Hemiparesis of patient left side", "Hemiparesis of patient right side", "Hemiplegia of patient right side", "Hemiplegia of patient left side"], answer: "Hemiplegia of patient right side" },
  { q: "What is a priority nursing assessment in the first 24 hours after admission of the patient with stroke:", options: ["Cholesterol level", "Glasgow Coma Scale", "Pain scale", "Echocardiogram"], answer: "Glasgow Coma Scale" },
  { q: "The neurologic functions that are affected by a stroke are primarily related:", options: ["The amount of tissue area involved", "The rapidity of onset of symptoms", "The brain area perfused by the affected artery", "The presence or absence of collateral circulation"], answer: "The brain area perfused by the affected artery" },
  { q: "When assessing a patient with a head injury, the nurse recognizes that the earliest indication of increased intracranial pressure (ICP) is:", options: ["Brain stem herniation", "Sluggish pupil response to light", "Projectile vomiting", "Change in level of consciousness"], answer: "Change in level of consciousness" },
  { q: "Which of the following values is considered normal for intracranial pressure?", options: ["10 to 20 mm Hg", "35 to 45 mm Hg", "25 mm Hg", "120/80 mm Hg"], answer: "10 to 20 mm Hg" },
  { q: "Which pt response in the motor component of the Glasgow Coma Scale would receive the largest score?", options: ["Extensor response", "Localizes", "Follows motor commands", "Withdraws"], answer: "Follows motor commands" },
  { q: "What is Glasgow Coma score of a client who withdraws from pain, converses but is confused, and opens his eyes spontaneously?", options: ["6", "9", "12", "15"], answer: "12" },
  { q: "The purpose of administering Erythropoietin hormone for patient with chronic renal failure:", options: ["Treatment of anemia", "Decrease level of creatinine", "Reduce hypercalcemia", "Prevent blood clot formation"], answer: "Treatment of anemia" },
  { q: "This is a phase of acute renal failure that characterized by decreasing of BUN & serum creatinine level:", options: ["Diuretic Phase", "Initiation phase", "Oliguric phase", "Recovery phase"], answer: "Recovery phase" },
  { q: "Mr. Ali has chronic kidney disease with GFR less than 15 mL/min. what is the stage of chronic kidney disease?", options: ["Stage 2", "Stage 3", "Stage 5", "Stage 4"], answer: "Stage 5" },
  { q: "Which of the following instructions the nurse should provide for patient with arteriovenous fistula?", options: ["Avoid sleep on arteriovenous fistula.", "Monitor blood pressure in the arm with fistula.", "Permit withdraw of blood sample from the fistula", "Wear constricted clothes on the affected arm"], answer: "Avoid sleep on arteriovenous fistula." },
  { q: "Which of the following is one of complications of peritoneal dialysis?", options: ["Air embolism", "Muscle cramping", "Hyperglycemia", "Dialysis disequilibrium syndrome"], answer: "Muscle cramping" },
  { q: "The average amount of protein intake in patient with chronic renal failure is:", options: ["150 gm/ daily", "200 gm/ daily", "50 gm/ daily", "100 gm/ daily"], answer: "50 gm/ daily" },
  { q: "All the following are describing the chronic renal failure Except:", options: ["Progressive and irreversible damage to the nephrons", "It may take months to years for developing.", "Can be treated by kidney transplantation.", "Can caused by bilateral renal vein thrombosis"], answer: "Can caused by bilateral renal vein thrombosis" },
  // True or False Section (180 - 200)
{ q: "During internal fixation metal implants are used to immobilize the fractured bone.", options: ["True", "False"], answer: "True" },
  { q: "The tumor suppressor genes are genes that inhibit cell division of cancer cell.", options: ["True", "False"], answer: "True" },
  { q: "Surgical removal of cancer is easier in benign than malignant tumor.", options: ["True", "False"], answer: "True" },
  { q: "Osteoarthritis is a degenerative disease that has systemic and local symptoms.", options: ["True", "False"], answer: "False" },
  { q: "The nurse should advise the patient with rheumatoid arthritis to lie on the abdomen (prone position) several times daily to prevent flexion deformities.", options: ["True", "False"], answer: "True" },
  { q: "An injection of glucagon can be administered either subcutaneously or intramuscularly for emergency treatment of hypoglycemia.", options: ["True", "False"], answer: "True" },
  { q: "In patient with Diabetes Mellitus, Postprandial glucose test is equal or greater than 200 mg/dL.", options: ["True", "False"], answer: "True" },
  { q: "IM administration of iron causes some local pain and possibly staining the skin.", options: ["True", "False"], answer: "True" },
  { q: "Oral iron supplements can cause gastrointestinal side effects.", options: ["True", "False"], answer: "True" },
  { q: "Primary hyperparathyroidism is diagnosed by persistent elevation of serum calcium levels and an elevated level of parathormone.", options: ["True", "False"], answer: "True" },
  { q: "Parenteral parathormone can be administered to treat acute hyperparathyroidism.", options: ["True", "False"], answer: "True" },
  { q: "Common side effects of corticosteroids include weight gain, swelling around the face and eyes, insomnia, bruising, gastric distress, gastric bleeding, and petechiae.", options: ["True", "False"], answer: "True" },
  { q: "Craniotomy refers to sudden loss of function resulting from a disruption of the blood supply to a part of the brain.", options: ["True", "False"], answer: "False" },
  { q: "In client with increased intracranial pressure keep Suctioning brief, without exceeding 15 seconds per pass of the catheter.", options: ["True", "False"], answer: "True" },
  { q: "Azotemia, means accumulation nitrogenous wastes such as creatinine and uric acid in the blood.", options: ["True", "False"], answer: "True" },
  { q: "The presence of thrill (vibration) in the site of arteriovenous fistula site indicates major complication.", options: ["True", "False"], answer: "False" },
  { q: "Acidosis is common in patients with renal failure.", options: ["True", "False"], answer: "True" },
  { q: "After the cast application the nurse should handle the wet cast with the palms of hand.", options: ["True", "False"], answer: "True" },
  { q: "Nurse should assess conscious level for patient recently diagnosed with stroke.", options: ["True", "False"], answer: "True" },
  { q: "According to medical management of stroke, the thrombolytic drugs used for prevention of hemorrhage.", options: ["True", "False"], answer: "False" },
  { q: "Patient age is considered a modifiable risk factor for cerebrovascular stroke occurrence.", options: ["True", "False"], answer: "False" }
];
const final2025Questions = [
  { q: "When taking a health history, the nurse screens for manifestations suggestive of diabetes type I. Which of the following manifestations are most suggestive of diabetes type I and require follow-up investigation?", options: ["Excessive intake of calories, rapid weight gain, and difficulty losing weight", "Poor circulation, wound healing, and leg ulcers", "Lack of energy, weight gain, and depression", "An increase in thirst, hunger and Frequent, high-volume urination"], answer: "An increase in thirst, hunger and Frequent, high-volume urination" },
  { q: "The newly diagnosed diabetic patient asks the nurse why he needs to check his feet every day. The nurse's best response is...", options: ["To prevent leg amputation", "To check for any cuts, sores, or dry cracked skin so they can be treated early to prevent infection or gangrene", "To see if they hurt", "You just need to do it"], answer: "To check for any cuts, sores, or dry cracked skin so they can be treated early to prevent infection or gangrene" },
  { q: "The nurse provides instructions to a client newly diagnosed with type 1 diabetes mellitus. The nurse recognizes accurate understanding of measures to prevent diabetic ketoacidosis when the client makes which statement?", options: ["'I will stop taking my insulin if I'm too sick to eat'.", "'I will decrease my insulin dose during times of illness'.", "'I will test blood glucose levels and urine ketones once a day and keep a record'", "'I will notify physician if my blood glucose level is higher than 300 mg/dL.'"], answer: "'I will notify physician if my blood glucose level is higher than 300 mg/dL.'" },
  { q: "A 54-year-old patient admitted with type 2 diabetes asks the nurse what 'type 2' means. What is the most appropriate response by the nurse?", options: ["'With type 2 diabetes, the body of the pancreas becomes inflamed'.", "'With type 2 diabetes, insulin secretion is decreased & insulin resistance is increased'.", "'With type 2 diabetes, the patient is totally dependent on an outside source of insulin.'", "'With type 2 diabetes, the body produces autoantibodies that destroy B-cells in the pancreas.'"], answer: "'With type 2 diabetes, insulin secretion is decreased & insulin resistance is increased'." },
  { q: "A patient arrives at the emergency department with a blood glucose of 578, severe thirst, dehydration, and confusion. The patient is breathing rapidly and has a fruity breath smell. This patient has symptoms of...", options: ["Diabetic ketoacidosis", "Normal findings", "Hypoglycemia", "Diabetic neuropathy"], answer: "Diabetic ketoacidosis" },
  { q: "Is a blood test that reflects average blood glucose levels over a period of approximately 2 to 3 months:", options: ["Fasting plasma glucose", "Random (casual) plasma glucose", "Glycosylated hemoglobin", "Two-hour postprandial glucose"], answer: "Glycosylated hemoglobin" },
  { q: "Is the major electrolyte of concern during treatment of diabetic ketoacidosis:", options: ["Sodium", "Potassium", "Magnesium", "Calcium"], answer: "Potassium" },
  { q: "The client is a 62-year-old woman who is overweight she comes to the doctor's office complaining of headaches, frequent anger, excessive thirst & urination. The presenting complaints suggest that the nurse should assess for other signs of which condition?", options: ["Hypothyroidism", "Hyperthyroidism", "Type 2 diabetes", "Type 1 diabetes"], answer: "Type 2 diabetes" },
  { q: "What should the nurse include in patient teaching regarding medications to treat DM?", options: ["Patients with type 1 diabetes may achieve normal blood glucose levels with oral medications", "Type 1 diabetes may progress to type 2 if blood glucose levels are not well controlled", "Patients with type 1 diabetes will always need an exogenous source of insulin", "Patients with type 2 diabetes generally need a combination of oral medications and insulin"], answer: "Patients with type 1 diabetes will always need an exogenous source of insulin" },
  { q: "Is characterized by destruction of the pancreatic beta cells:", options: ["Type 2 diabetes", "Gestational diabetes", "Type 1 Diabetes", "Prediabetes"], answer: "Type 1 Diabetes" },
  { q: "The nurse is working with a person who was just diagnosed with diabetes mellitus Type 2 What should the nurse teach the client first?", options: ["How to self-inject insulin", "How to follow a diabetic diet", "Signs and symptoms of insulin reaction", "Complications of diabetes"], answer: "How to follow a diabetic diet" },
  { q: "The client is diagnosed with hyperthyroidism. All the following the nurse will expect the client to exhibit EXCEPT?", options: ["Complaints of extreme fatigue and hair loss", "Exophthalmos and complaints of nervousness", "Complaints of profuse sweating and flushed skin", "Increased appetite and weight loss"], answer: "Complaints of extreme fatigue and hair loss" },
  { q: "Is the preferred preparation for treating hypothyroidism.", options: ["Beta-blocker agents", "Propylthiouracil", "Synthetic levothyroxine", "Radioactive iodine"], answer: "Synthetic levothyroxine" },
  { q: "A female patient is admitted with complaints of palpitations, excessive sweating, and unable to tolerate heat... protruding eyeballs. Which of the following is the likely cause of the patient's signs and symptoms?", options: ["Grave's Disease", "Thyroiditis", "Hypothyroidism", "Myxedema coma"], answer: "Grave's Disease" },
  { q: "Which medication order should the nurse give with caution in the client diagnosed with untreated hypothyroidism?", options: ["Sedatives", "Laxatives", "Thyroid hormones", "Oxygen"], answer: "Sedatives" },
  { q: "Which of the following can represent a medical management for patient with anemia of chronic disease?", options: ["Bone marrow transplant", "Iron supplementation", "Treatment of the underlying disorder", "Immunosuppressive therapy"], answer: "Treatment of the underlying disorder" },
  { q: "The nurse is caring for a client who is thought to have Megaloblastic Anemia. What signs and symptoms would the nurse expect in this person?", options: ["Signs of infection and bleeding", "Craving for ice or dirt", "Numbness and tingling in the feet and lower legs", "Jaundice and is usually obvious in the sclerae"], answer: "Numbness and tingling in the feet and lower legs" },
  { q: "An adult is admitted to the hospital with a diagnosis of hypothyroidism. Which findings would the nurse most likely elicit during the nursing assessment?", options: ["Elevated blood pressure & tachycardia", "Increased appetite and weight loss", "Hypothermia and constipation", "Moist and flushed skin"], answer: "Hypothermia and constipation" },
  { q: "Which nursing diagnosis takes highest priority for a client with hyperthyroidism?", options: ["Risk for imbalanced nutrition: More than body requirement", "Risk for impaired skin integrity", "Imbalanced nutrition: Less than body requirements", "Body image disturbance"], answer: "Imbalanced nutrition: Less than body requirements" },
  { q: "Ferrous sulfate is prescribed for a client... Which assessment by the nurse indicates that she has NOT been taking iron as ordered?", options: ["The client's cheeks are flushed", "The client complains of nausea", "The client reports having more energy", "The client's stools are light brown"], answer: "The client's stools are light brown" },
  { q: "The nurse administers iron using the Z track technique. What is the primary reason for administering iron via Z track?", options: ["To prevent adverse reactions", "To improve the absorption rate", "To prevent pain & staining of the skin", "To increase the speed of onset of action"], answer: "To prevent pain & staining of the skin" },
  { q: "The physician has recommended that the client increase the amount of dietary iron. The nurse knows that the client understands when the client selects which foods?", options: ["Orange juice, scrambled eggs & toast", "Roast beef, carrots, and rice", "Hot dog and roll, French fries & cola", "Baked chicken, peas, and noodles"], answer: "Roast beef, carrots, and rice" },
  { q: "Which of the following values is considered normal for intracranial pressure?", options: ["10 to 20 mm Hg", "35 to 45 mm Hg", "25 mm Hg", "120/80 mm Hg"], answer: "10 to 20 mm Hg" },
  { q: "To maintain effective cerebral tissue perfusion related to increased ICP, the nurse should do all of the following EXCEPT:", options: ["Avoid extreme hip flexion", "Keep the patient in flat position", "Avoid ROM exercises until ICP approaches normal", "Give diuretics as prescribed"], answer: "Keep the patient in flat position" },
  { q: "A patient is admitted with diabetes mellitus. What type of stroke is this patient at MOST risk for?", options: ["Ischemic stroke", "Hemorrhagic stroke", "Increase intracranial pressure", "Encephalopathy"], answer: "Ischemic stroke" },
  { q: "Stroke patient suffered from difficulty of swallowing... nurse should put this patient in which position?", options: ["Fowler position", "Flat position", "Right lateral position", "Left recumbent position"], answer: "Fowler position" },
  { q: "Involves opening the skull surgically to gain access to intracranial structures:", options: ["Coma", "Stroke", "Increased intracranial pressure", "Craniotomy"], answer: "Craniotomy" },
  { q: "To maintain effective cerebral tissue perfusion related to increased ICP, the nurse should do all of the following EXCEPT:", options: ["Avoid extreme hip flexion", "Keep the patient in flat position", "Avoid ROM exercises until ICP approaches normal", "Give diuretics as prescribed"], answer: "Keep the patient in flat position" },
  { q: "What is a priority nursing assessment in the first 24 hours after admission of the patient with stroke?", options: ["Pain scale", "Echocardiogram", "Cholesterol level", "Glasgow Coma Scale"], answer: "Glasgow Coma Scale" },
  { q: "A patient experience numbness... symptoms disappear... importance of evaluation:", options: ["Asymptomatic stroke", "Symptoms likely to return in 24 hours", "Result of small hemorrhages", "Transient ischemic attack (TIA)"], answer: "Transient ischemic attack (TIA)" },
  { q: "A client with hemorrhagic stroke becomes restless and confused. Mannitol is ordered for:", options: ["Reduce intraocular pressure", "Prevent acute tubular necrosis", "Promote osmotic diuresis to reduce cerebral edema", "Draw water into vascular system"], answer: "Promote osmotic diuresis to reduce cerebral edema" },
  { q: "The neurologic functions that are affected by a stroke are primarily related to:", options: ["Amount of tissue area involved", "Rapidity of onset of symptoms", "Brain area perfused by the affected artery", "Presence of collateral circulation"], answer: "Brain area perfused by the affected artery" },
  { q: "What is the type of fracture that broken bone associated with an open wound?", options: ["Impacted fracture", "Compound fracture", "Comminuted fracture", "Complete fracture"], answer: "Compound fracture" },
  { q: "Pathological type of fracture can result from...", options: ["Diseases as osteoporosis", "Sudden twist", "Crushing force", "External muscles contraction"], answer: "Diseases as osteoporosis" },
  { q: "In case of fracture with external bleeding, the nurse should control the bleeding by:", options: ["Use of splint", "Immobilizes the affected part", "Vitamin K intramuscular", "Use gentle pressure above bleeding area"], answer: "Use gentle pressure above bleeding area" },
  { q: "Hip fracture skin traction temporary treatment. Nurse should assess neurovascular status every:", options: ["15-30 minutes", "Every two hours", "Every 3 hours", "Every 4 hours"], answer: "Every 4 hours" },
  { q: "Contraction and relaxation of muscles without joint movement. Type of exercises:", options: ["Isometric exercises", "Range of Motion exercises", "Isotonic exercises", "All of the above"], answer: "Isometric exercises" },
  { q: "Which statement by a patient with a cast requires immediate notification of physician?", options: ["It is really itchy inside my cast", "I can feel my fingers and move them", "Pain is so severe that it hurts to stretch or elevate my arm", "I've been using ice packs"], answer: "Pain is so severe that it hurts to stretch or elevate my arm" },
  { q: "Follow up of external fixation device, important point to assess:", options: ["Pin site infection", "Ability of bearing down", "Healing process", "Nutritional status"], answer: "Pin site infection" },
  { q: "Purpose of using canes or walkers for rheumatoid arthritis patient:", options: ["Prevent fall", "Help in correct walk", "Restore joint mobility", "Reduce amount of weight bearing on joints"], answer: "Reduce amount of weight bearing on joints" },
  { q: "Arthroplasty refers to:", options: ["Surgical fusion", "Excision of synovial membrane", "Suturing of tendon", "Surgical replacement of joint"], answer: "Surgical replacement of joint" },
  { q: "Injecting gel-like substances into knee joint for osteoarthritis aim:", options: ["Prevent loss of cartilage", "Prevent deformity", "Reduce pain", "Reduce inflammation"], answer: "Reduce pain" },
  { q: "To prevent kyphosis for patients with rheumatoid arthritis, advising to sleep in:", options: ["Fowler position", "Side lying", "Flat on firm mattress, only one pillow under head", "Flat on soft mattress"], answer: "Flat on firm mattress, only one pillow under head" },
  { q: "Risk factors of osteoarthritis EXCEPT:", options: ["Older age", "Female gender", "Obesity", "Young age"], answer: "Young age" },
  { q: "Most accurate way to monitor kidney function in CKD:", options: ["Monitor intake & output", "Check urine specific gravity", "Check bun & serum creatinine level", "Check x ray reports"], answer: "Check bun & serum creatinine level" },
  { q: "Immunosuppressive drugs are taken with:", options: ["Hemodialysis", "Peritoneal dialysis", "Kidney transplant", "Major viruses"], answer: "Kidney transplant" },
  { q: "Abnormal connection between artery and vein created for hemodialysis:", options: ["Arteriovenous fistula", "Hemodialysis", "Peritoneal dialysis", "Period of diuresis"], answer: "Arteriovenous fistula" },
  { q: "How often must hemodialysis usually be done?", options: ["Every day", "Twice a week", "Once a week", "3 times a week"], answer: "3 times a week" },
  { q: "According to staging of tumor, stage IV means:", options: ["Limited local spread", "Extensive local and regional spread", "Cancer in situ", "Metastasis"], answer: "Metastasis" },
  { q: "Carcinomas means:", options: ["Growing of epithelial cells & usually solid tumors", "Arising from lymphoid tissue", "Arising from muscle, bone, fat, or connective tissue", "Arising from the anatomic site/ tissue of origin"], answer: "Growing of epithelial cells & usually solid tumors" },
  { q: "Burn location most at risk of life-threatening complications:", options: ["Lower torso", "Upper part of the body", "Hands and feet", "Perineum"], answer: "Upper part of the body" },
  { q: "Priority nursing observation first 48 hours after burn:", options: ["Hourly blood pressure", "Hourly Urine output", "Assessment of skin color", "Frequent assessment for pain"], answer: "Hourly Urine output" },
  { q: "Which skin lesion should be reported immediately?", options: ["Small mole same since childhood", "Pigmented area present since birth", "Small warts", "Black and purple mole growing larger and changing shape"], answer: "Black and purple mole growing larger and changing shape" },
  { q: "Burn wound tissue shortens because of force of fibroblasts:", options: ["Keloids", "Scares", "Contracture", "Debris"], answer: "Contracture" },
  { q: "Burn caused by fires, steam or hot fluids:", options: ["Chemical burns", "Electrical burns", "Thermal burns", "Radiation Burns"], answer: "Thermal burns" },
  { q: "Burn extends to epidermis and deeper dermis:", options: ["Superficial partial-thickness burns", "Deep partial-thickness burns", "Full-thickness burn", "Keloids"], answer: "Deep partial-thickness burns" },

  // --- True / False Section (57 - 82) ---
  { q: "Maintain effective traction by assuring prescribed weight is hanging free.", options: ["True", "False"], answer: "True" },
  { q: "During closed reduction plates and pins are used to hold fragments.", options: ["True", "False"], answer: "False" },
  { q: "Buck's extension traction is balanced suspension traction.", options: ["True", "False"], answer: "False" },
  { q: "Rheumatoid arthritis patient lie on abdomen prone to prevent flexion deformities.", options: ["True", "False"], answer: "True" },
  { q: "Glucagon injection for emergency treatment of hypoglycemia.", options: ["True", "False"], answer: "True" },
  { q: "In DM, Postprandial glucose test is >= 200 mg/dL.", options: ["True", "False"], answer: "True" },
  { q: "Sodium is major electrolyte of concern during DKA treatment.", options: ["True", "False"], answer: "False" },
  { q: "Keep suctioning brief, not exceeding 15 seconds for ICP client.", options: ["True", "False"], answer: "True" },
  { q: "In elevated ICP, coughing is encouraged to clear secretions.", options: ["True", "False"], answer: "False" },
  { q: "Synthetic levothyroxine is preferred for hyperthyroidism.", options: ["True", "False"], answer: "False" },
  { q: "Thyroid storm is precipitated by stress (DKA, emotional stress).", options: ["True", "False"], answer: "True" },
  { q: "Heat intolerance is manifestation of hypothyroidism.", options: ["True", "False"], answer: "False" },
  { q: "Erythropoietin purpose in CRF is to decrease creatinine.", options: ["True", "False"], answer: "False" },
  { q: "Risk factors for cancer include heredity, age, stress.", options: ["True", "False"], answer: "True" },
  { q: "Growth in benign tumor is rapid and infiltrates surrounding tissues.", options: ["True", "False"], answer: "False" },
  { q: "Chemotherapy eradicates cells in process of reproduction.", options: ["True", "False"], answer: "True" },
  { q: "Potassium intake should be increased in patient with chronic renal failure.", options: ["True", "False"], answer: "False" },
  { q: "Patient's weight assessed in Pre and post dialysis care.", options: ["True", "False"], answer: "True" },
  { q: "B12 deficiency can occur in strict vegetarians.", options: ["True", "False"], answer: "True" },
  { q: "In Sickle cell anemia; Jaundice is characteristic in sclerae.", options: ["True", "False"], answer: "True" },
  { q: "Beans and Molasses are high in iron.", options: ["True", "False"], answer: "True" },
  { q: "In burn, Hyperkalemia and Hyponatremia are main imbalances.", options: ["True", "False"], answer: "True" },
  { q: "Rule of nines is used to determine depth of burn injury.", options: ["True", "False"], answer: "False" },
  { q: "Paralytic ileus may develop due to burn.", options: ["True", "False"], answer: "True" },
  { q: "Grafting burn occurs when spontaneous revitalization is impossible.", options: ["True", "False"], answer: "True" },
  { q: "Adult thermal burn urine output should be > 30ml/hr.", options: ["True", "False"], answer: "false" }
];
;
// 2. قائمة التصنيفات وربط الأزرار
const categories = [
    { id: 'Mid term 2026', array: mid2026Questions },
    { id: 'Mid term 2025', array: mid2025Questions },
    { id: 'Mid term 2023', array: mid2023Questions },
    { id: 'كويزات سابقة', array: previousQuizzesQuestions, special: true },
    { id: 'Final Summer 2024', array: finalSummer2024Questions },
    { id: 'Final 2024', array: final2024Questions },
    { id: 'Final 2025', array: final2025Questions }
];

const menuArea = document.getElementById('menu-items');
categories.forEach(cat => {
    const style = cat.special ? 'style="border-color: #e67e22;"' : '';
    menuArea.innerHTML += `<div class="nav-item" ${style} onclick="openPage('${cat.id}')">${cat.id} <span>←</span></div>`;
});

function openPage(title) {
    document.getElementById('main-menu').style.display = 'none';
    document.getElementById('quiz-page').style.display = 'block';
    document.getElementById('quiz-title').innerText = title;
    const area = document.getElementById('questions-area');
    area.innerHTML = ''; 

    let data = categories.find(c => c.id === title).array;
    if (!data || data.length === 0) {
        area.innerHTML = '<p style="text-align:center; padding:50px;">ابعتيلي الأسئلة يا منار عشان أضيفها هنا! 😉</p>';
        return;
    }

    data.forEach((item, index) => {
        let opts = item.options.map((o, idx) => {
            const letters = ['a', 'b', 'c', 'd'];
            let isCorrect = false;
            if (item.answer.toLowerCase() === 'true' && o === 'True') isCorrect = true;
            else if (item.answer.toLowerCase() === 'false' && o === 'False') isCorrect = true;
            else if (item.answer.toLowerCase() === letters[idx]) isCorrect = true;
            return `<div class="option" onclick="check(this, ${isCorrect})">${o}</div>`;
        }).join('');
        area.innerHTML += `<div class="question-box"><p><b>${index+1}.</b> ${item.q}</p>${opts}</div>`;
    });
    window.scrollTo(0,0);
}

function closePage() {
    document.getElementById('quiz-page').style.display = 'none';
    document.getElementById('main-menu').style.display = 'block';
}

function check(el, isCorrect) {
    if (el.parentElement.classList.contains('done')) return;
    const options = el.parentElement.querySelectorAll('.option');
    if(isCorrect) el.classList.add('correct');
    else {
        el.classList.add('wrong');
        options.forEach(o => { if(o.getAttribute('onclick').includes('true')) o.classList.add('correct'); });
    }
    el.parentElement.classList.add('done');
}
</script>
</body>
</html>
