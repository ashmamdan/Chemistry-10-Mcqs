# Chemistry-10-Mcqs
Mcqs preparation 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Punjab Chemistry MCQ Practice</title>

<style>
*{box-sizing:border-box}
body{margin:0;font-family:Arial,sans-serif;background:#f5f7fb;color:#172033}
button,select{font:inherit}
button{cursor:pointer}

.wrap{max-width:1050px;margin:auto;padding:24px 15px 45px}
.head{display:flex;justify-content:space-between;gap:12px;margin-bottom:22px}
.head h1{margin:5px 0;font-size:32px}
.muted{color:#687386}
.badge,.pill{background:#e9efff;color:#3155d9;padding:7px 11px;border-radius:99px;font-size:11px;font-weight:bold}

.stats{
display:grid;
grid-template-columns:repeat(6,1fr);
background:white;
border:1px solid #e4e8ef;
border-radius:16px;
overflow:hidden;
margin-bottom:20px
}
.stat{text-align:center;padding:14px 5px;border-right:1px solid #edf0f5}
.stat:last-child{border:0}
.stat b{display:block;font-size:21px}
.stat span{font-size:9px;color:#7b8798;text-transform:uppercase}

.hero{
background:#111827;
color:#fff;
border-radius:18px;
padding:24px;
display:flex;
align-items:center;
justify-content:space-between;
gap:15px;
margin-bottom:27px
}
.hero h2{margin:6px 0}
.hero p{margin:0;color:#aeb8c9}

.primary{
border:0;
background:#3155d9;
color:#fff;
border-radius:10px;
padding:12px 16px;
font-weight:bold
}

.title{
display:flex;
justify-content:space-between;
align-items:center;
margin:12px 0
}
.title h2{font-size:18px;margin:0}
.title span{font-size:11px;color:#7b8798}

.grid{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:11px
}

.paper{
background:#fff;
border:1px solid #e1e6ee;
border-radius:13px;
padding:15px;
display:flex;
align-items:center;
gap:13px;
text-align:left
}

.paper:hover{border-color:#aab8df}

.num{
width:39px;
height:39px;
background:#f0f3f9;
border-radius:10px;
display:grid;
place-items:center;
font-weight:bold;
font-size:12px
}

.paper small{
display:block;
color:#7b8798;
margin-top:4px
}

.arrow{margin-left:auto}

.panels{
display:grid;
grid-template-columns:1fr 1fr;
gap:14px;
margin-top:23px
}

.panel{
background:#fff;
border:1px solid #e4e8ef;
border-radius:14px;
padding:16px
}

.random{
display:grid;
grid-template-columns:1fr 1fr;
gap:9px
}

.random button{
border:1px solid #e1e6ee;
background:#fafbfe;
border-radius:10px;
padding:13px;
text-align:left
}

.random span{
display:block;
color:#7b8798;
font-size:11px;
margin-top:4px
}

select{
width:100%;
padding:11px;
border:1px solid #dbe1ea;
border-radius:9px;
background:#fff;
margin-bottom:9px
}

.check{
font-size:12px;
color:#687386;
display:block;
margin-bottom:12px
}

footer{
display:flex;
justify-content:space-between;
color:#8b95a5;
font-size:11px;
margin-top:24px
}

/* TEST */

.test{
min-height:100vh;
background:#f6f8fc
}

.bar{
height:63px;
background:#fff;
border-bottom:1px solid #e5eaf2;
display:flex;
align-items:center;
justify-content:space-between;
padding:0 15px
}

.exit{
border:0;
background:none;
color:#687386
}

.barcenter{text-align:center}
.barcenter b{display:block;font-size:13px}
.barcenter span{font-size:10px;color:#7b8798}

.timer{
background:#eef2ff;
color:#3155d9;
padding:9px 11px;
border-radius:9px;
font-weight:bold
}

.prog{
height:4px;
background:#e8ecf3
}

.prog div{
height:100%;
background:#3155d9
}

.main{
max-width:800px;
margin:28px auto;
padding:0 16px 45px
}

.qtop{
display:flex;
justify-content:space-between;
align-items:center
}

.flag{
border:0;
background:none;
color:#7b8798;
font-size:11px
}

.flag.on{color:#b87800}

.section{
font-size:11px;
color:#7b8798;
margin:20px 0 8px
}

.question{
font-size:25px;
line-height:1.3;
margin:0 0 21px
}

.opts{
display:grid;
gap:9px
}

.opt{
width:100%;
display:flex;
align-items:center;
gap:12px;
text-align:left;
background:#fff;
border:1px solid #dfe5ee;
border-radius:12px;
padding:14px
}

.opt.sel{
background:#eef2ff;
border-color:#3155d9
}

.letter{
width:31px;
height:31px;
border:1px solid #d7ddea;
border-radius:8px;
display:grid;
place-items:center;
font-weight:bold;
font-size:11px;
flex:none
}

.sel .letter{
background:#3155d9;
color:#fff;
border-color:#3155d9
}

.nav{
display:flex;
justify-content:space-between;
margin:23px 0
}

.nav button:not(.primary):not(.submit){
background:#fff;
border:1px solid #dfe4ec;
border-radius:9px;
padding:10px 14px
}

.submit{
background:#198754;
color:#fff;
border:0;
border-radius:9px;
padding:10px 15px;
font-weight:bold
}

.palette{
background:#fff;
border:1px solid #e3e8ef;
border-radius:13px;
padding:13px
}

.phead{
display:flex;
justify-content:space-between;
font-size:11px;
margin-bottom:10px
}

.phead span{color:#7b8798}

.dots{
display:flex;
flex-wrap:wrap;
gap:5px
}

.dots button{
width:32px;
height:29px;
border:1px solid #dfe5ed;
background:#fff;
border-radius:7px;
font-size:10px
}

.dots .ans{background:#e9eefc}
.dots .cur{outline:2px solid #3155d9}
.dots .mark{box-shadow:inset 0 -3px #e4a72c}

/* RESULT */

.result{
max-width:900px;
margin:auto;
padding:30px 15px
}

.resultbox{
text-align:center;
background:#fff;
border:1px solid #e3e8ef;
border-radius:18px;
padding:30px
}

.score{
font-size:60px;
font-weight:bold;
margin:8px
}

.rg{
display:grid;
grid-template-columns:repeat(3,1fr);
max-width:500px;
margin:20px auto;
border-top:1px solid #edf0f5;
border-bottom:1px solid #edf0f5
}

.rg div{
padding:13px;
border-right:1px solid #edf0f5
}

.rg div:last-child{border:0}

.rg b,.rg span{display:block}
.rg span{
font-size:10px;
color:#7b8798;
margin-top:3px
}

.actions{
display:flex;
justify-content:center;
gap:8px
}

.actions button:not(.primary){
background:#fff;
border:1px solid #dfe4ec;
border-radius:9px;
padding:11px 15px
}

.review{margin-top:22px}

.reviewitem{
background:#fff;
border:1px solid #e3e8ef;
border-left:4px solid #e05b5b;
border-radius:8px;
padding:11px;
margin:7px 0;
font-size:12px
}

.reviewitem.ok{border-left-color:#2e9d61}

.reviewitem small{
display:block;
color:#687386;
margin-top:5px
}

@media(max-width:700px){

.head h1{font-size:25px}
.badge{display:none}

.stats{
grid-template-columns:repeat(3,1fr)
}

.stat:nth-child(3){border-right:0}

.stat:nth-child(-n+3){
border-bottom:1px solid #edf0f5
}

.hero{display:block}

.hero .primary{
width:100%;
margin-top:15px
}

.grid,.panels{
grid-template-columns:1fr
}

.question{font-size:21px}

.bar{padding:0 10px}

.result{
padding:20px 10px
}

footer{display:block}

footer span{
display:block;
margin-top:5px
}

}
</style>
</head>

<body>

<div id="app"></div>

<script>

/* =========================================================
   MCQ DATABASE
   ========================================================= */

const Q=[

["Paper 08","Chapter 16 — Chemical Industries","Froth flotation process is used to concentrate ore on which basis?","Density basis","Concentration basis","Wetting basis","Magnetic basis","C"],
["Paper 08","Chapter 16 — Chemical Industries","Concentration of copper ore is carried out by:","Calcination","Roasting","Froth flotation","Distillation","C"],
["Paper 08","Chapter 16 — Chemical Industries","What is the formula of urea?","NH₂COONH₄","NH₂COONH₂","NH₂COOH","NH₂CONH₂","D"],
["Paper 08","Chapter 16 — Chemical Industries","Red hair contains a compound of:","Iron","Copper","Titanium","Molybdenum","D"],
["Paper 08","Chapter 16 — Chemical Industries","When CO₂ is passed through ammoniacal brine, the only salt that precipitates is:","NaHCO₃","NH₄HCO₃","Na₂CO₃","(NH₄)₂CO₃","A"],
["Paper 08","Chapter 16 — Chemical Industries","In Solvay's process, NaHCO₃ can be obtained by maintaining the temperature at:","10°C","15°C","20°C","25°C","B"],
["Paper 08","Chapter 16 — Chemical Industries","The nitrogen present in urea is used by plants to synthesize:","Sugar","Protein","Fats","DNA","B"],
["Paper 08","Chapter 16 — Chemical Industries","Which is a raw material for urea?","CO","CO₂","N₂","NO₂","B"],
["Paper 08","Chapter 16 — Chemical Industries","Which is NOT a fraction of petroleum?","Kerosene oil","Diesel oil","Alcohol","Petrol","C"],
["Paper 08","Chapter 16 — Chemical Industries","What is the carbon range in fuel oil?","C₇ to C₁₀","C₁₀ to C₁₂","C₁₃ to C₁₅","C₁₅ to C₁₈","D"],
["Paper 08","Chapter 16 — Chemical Industries","Which is a fraction of residual oil?","Petroleum gas","Petroleum ether","Diesel oil","Lubricants","D"],
["Paper 08","Chapter 16 — Chemical Industries","Which is a fraction of residual oil?","Kerosene oil","Asphalt","Petrol","Petroleum ether","B"],

["Paper 09","First Quarter — Units 9 to 11","Substances formed during a chemical reaction are called:","Products","Reactants","Radicals","Elements","A"],
["Paper 09","First Quarter — Units 9 to 11","Molar concentration is expressed in:","{ }","[ ]","( )","All of these","B"],
["Paper 09","First Quarter — Units 9 to 11","The value of Kc depends upon:","Pressure","Temperature","Volume","Density","B"],
["Paper 09","First Quarter — Units 9 to 11","If Qc > Kc, the reaction will proceed in the:","Chemical equilibrium","Static equilibrium","Reverse direction","Forward direction","C"],
["Paper 09","First Quarter — Units 9 to 11","Malic acid is found in:","Lemon","Sour milk","Orange","Apple","D"],
["Paper 09","First Quarter — Units 9 to 11","What is the chemical formula of sulphuric acid?","H₂SO₄","HCl","HNO₃","NaCl","A"],
["Paper 09","First Quarter — Units 9 to 11","Arrhenius concept is applicable in:","Non-aqueous medium","Aqueous medium","Alcoholic medium","Basic medium","B"],
["Paper 09","First Quarter — Units 9 to 11","Which is NOT composed of salt?","A metallic cation","A non-metallic cation","An anion of a base","An anion of an acid","B"],
["Paper 09","First Quarter — Units 9 to 11","What is the formula of pentane?","C₅H₁₂","C₅H₁₀","C₅H₈","C₅H₁₄","A"],
["Paper 09","First Quarter — Units 9 to 11","The benzene ring is an example of:","Alicyclic compound","Aromatic compound","Heterocyclic compound","Straight-chain compound","B"],
["Paper 09","First Quarter — Units 9 to 11","Conversion of dead plants into coal by the action of bacteria and heat is called:","Carbonization","Catenation","Hydrogenation","Cracking","A"],
["Paper 09","First Quarter — Units 9 to 11","Which compound is a ketone?","(CH₃)₂CHOH","(CH₃)₂CO","(CH₃)₂NH","(CH₃)₂CHCl","B"],

["Paper 10","Second Quarter — Units 12 to 14","Incomplete combustion of alkanes produces:","Carbon dioxide only","Carbon monoxide only","Carbon monoxide and carbon black","Carbon dioxide and carbon black","C"],
["Paper 10","Second Quarter — Units 12 to 14","A hydrocarbon reacts with one mole of H₂ to form a saturated hydrocarbon. A possible formula of X is:","C₃H₈","C₆H₁₂","C₄H₁₀","C₇H₁₆","B"],
["Paper 10","Second Quarter — Units 12 to 14","Hydrogenation of CH₂=CH₂ uses which catalyst?","Ni","Na","Mg","Ca","A"],
["Paper 10","Second Quarter — Units 12 to 14","The end product of oxidation of acetylene is:","Oxalic acid","Glycol","Glyoxal","None","A"],
["Paper 10","Second Quarter — Units 12 to 14","Which of the following is a triglyceride?","Carbohydrates","Proteins","Lipids","Vitamins","C"],
["Paper 10","Second Quarter — Units 12 to 14","Pentahydroxy ketone is called:","Glucose","Starch","Sucrose","Fructose","D"],
["Paper 10","Second Quarter — Units 12 to 14","Which is responsible for transmitting genetic information from one generation to the next?","Protein","Nucleic acid","Carbohydrates","Lipids","B"],
["Paper 10","Second Quarter — Units 12 to 14","The scientific name of vitamin C is:","Acetic acid","Formic acid","Ascorbic acid","Lactic acid","C"],
["Paper 10","Second Quarter — Units 12 to 14","The temperature range of the stratosphere is approximately:","7°C to −91°C","2°C to −93°C","17°C to −58°C","−58°C to −2°C","D"],
["Paper 10","Second Quarter — Units 12 to 14","Ozone is formed in the:","Troposphere","Stratosphere","Mesosphere","Thermosphere","B"],
["Paper 10","Second Quarter — Units 12 to 14","Atmospheric temperature increases every year due to accumulation of CO₂ by about:","0.01°C","0.05°C","0.09°C","0.013°C","B"],
["Paper 10","Second Quarter — Units 12 to 14","The pH of acid rain is about:","4","6","6.5","2","A"],

["Paper 11","Third Quarter — Units 15 to 16","Water has maximum density at:","0°C","100°C","4°C","−4°C","C"],
["Paper 11","Third Quarter — Units 15 to 16","The percentage of water in the human body is about:","68%","69%","70%","71%","C"],
["Paper 11","Third Quarter — Units 15 to 16","Hardness of water is of how many types?","2","3","4","5","A"],
["Paper 11","Third Quarter — Units 15 to 16","Which salt makes water permanently hard?","Na₂CO₃","NaHCO₂","Ca(HCO₃)₂","CaSO₄","D"],
["Paper 11","Third Quarter — Units 15 to 16","Rapid algae growth in water bodies due to detergents is caused by:","Carbonate salts","Sulphonic acid salts","Sulphate salts","Phosphate salts","D"],
["Paper 11","Third Quarter — Units 15 to 16","Which disease causes severe diarrhea and can be fatal?","Jaundice","Dysentery","Cholera","Typhoid","C"],
["Paper 11","Third Quarter — Units 15 to 16","The chemical formula of chalcopyrite is:","Cu₂S","CuFeS₂","CuS","FeS","B"],
["Paper 11","Third Quarter — Units 15 to 16","Copper pyrite strongly heated in excess air converts into a mixture of:","Cu₂O and FeS","Cu₂O and FeS₂","Cu₂S and FeS","Cu₂O and SO₂","C"],
["Paper 11","Third Quarter — Units 15 to 16","A vigorous reaction of water with ___ can shatter glassware into small pieces.","Sodium","Caesium","Strontium","Silicon","B"],
["Paper 11","Third Quarter — Units 15 to 16","The nitrogen in urea is used by plants to synthesize:","Sugar","Proteins","Fats","DNA","B"],
["Paper 11","Third Quarter — Units 15 to 16","Concentration is a:","Mixing technique","Separating technique","Boiling technique","Cooling technique","B"],
["Paper 11","Third Quarter — Units 15 to 16","The boiling range of petroleum ether is:","170–250°C","30–80°C","20–170°C","80–170°C","B"],

["Paper 12","First Half Book — Chapters 9 to 12","In a chemical reaction, substances that combine are called:","Reactants","Products","Equilibrium","Numerator","A"],
["Paper 12","First Half Book — Chapters 9 to 12","For N₂ + 3H₂ ⇌ 2NH₃, the equilibrium constant expression is:","[2NH₃]²/[N₂][H₂]³","[NH₃]²/[N₂][H₂]³","[N₂][H₂]³/[NH₃]²","[NH₃]/[N₂][H₂]","B"],
["Paper 12","First Half Book — Chapters 9 to 12","If Qc > Kc, the reaction will proceed in the:","Chemical equilibrium","Static equilibrium","Reverse direction","Forward direction","C"],
["Paper 12","First Half Book — Chapters 9 to 12","Which species is NOT amphoteric?","H₂O","NH₃","HCO₃⁻","SO₄²⁻","D"],
["Paper 12","First Half Book — Chapters 9 to 12","Which base is used in alkaline batteries?","NaOH","Al(OH)₃","KOH","Mg(OH)₂","C"],
["Paper 12","First Half Book — Chapters 9 to 12","Which base is used to neutralize acidity in the stomach?","Ca(OH)₂","NaOH","Mg(OH)₂","KOH","C"],
["Paper 12","First Half Book — Chapters 9 to 12","What is the colour of Ca(OH)₂?","Blue","Green","White","Red","C"],
["Paper 12","First Half Book — Chapters 9 to 12","Which is NOT a mineral acid?","HCl","H₂SO₄","HNO₃","H₂CO₃","D"],
["Paper 12","First Half Book — Chapters 9 to 12","The total number of elements known till now is:","102","109","118","126","C"],
["Paper 12","First Half Book — Chapters 9 to 12","Besides valuable chemicals, the black residue of coal tar is called:","Peat","Pitch","Coke","Lignite","B"],
["Paper 12","First Half Book — Chapters 9 to 12","Which is a substitution reaction?","Halogenation of alkynes","Halogenation of alkenes","Halogenation of alkanes","Bromination of alkenes","C"],
["Paper 12","First Half Book — Chapters 9 to 12","Oxidation of alkenes produces:","Glyoxal","Glycol","Oxalic acid","Formic acid","B"],

["Paper 13","Second Half Book — Chapters 13 to 16","A pentahydroxy aldehyde is:","Starch","Glucose","Fructose","Sucrose","B"],
["Paper 13","Second Half Book — Chapters 13 to 16","The source of galactose is:","F |oai:code-citation|
