# Cement-Clinker-Strength-Prediction-Model
In this repository an attempt is made to predict cement clinker strength with the help of linear regression model  

# Cement/Clinker strength prediction model

Let’s have a quick introduction about clinker and the details of the dataset used:

Clinker is a nodular material produced in the kilning stage during the production of cement and is used as the binder in many cement products. The lumps or nodules of clinker are usually of diameter 3-25 mm and dark grey in color. It is produced by heating limestone and clay to the point of liquefaction at about 1400°C-1500°C in the rotary kiln. Clinker, when added with gypsum (to control the setting properties of cement and ensure compressive strength) and ground finely, produces cement. Clinker can be stored for long periods of time in a dry condition without degradation of quality, hence it is traded internationally and used by cement manufacturers when raw materials are found to be scarce or unavailable. 
(Sources: (1) https://www.hindawi.com/journals/ijac/2016/1259094/
          (2) https://civiltoday.com/civil-engineering-materials/cement/108-what-is-cement-clinker-clinker-definition-composition-types-uses 
          (3) https://en.wikipedia.org/wiki/Cement_clinker)

In the clinker, the following predominate chemicals elements are Ca, Si, Al, Fe, Mg, Na, and K. These elements are expressed as a percentage of oxides. These elements are expressed as a percentage of oxides and the Bogue notation is used to refer to them: CaO = C, Al2O3 = A, SiO2 = S, Fe2O3 = F, and MgO = M. Despite the wide variety of clinker phases, only four of them are, in practice, of real importance: silicates including alite (C3S = Ca3SiO5 = 3CaO-SiO2) give the hydrated cement short-term resistance; belite (C2S = Ca2SiO4 = 2CaO-SiO2) which confers long-term resistance to the finished product; aluminates consisting of tricalcium aluminate (C3A = Ca3Al2O6 = 3CaO-Al2O3) and aluminoferrites (C4AF = Ca4Al2 Fe2O10 = 4CaO-Fe2O3-Al2O3).

Now let’s have a quick info on columns, the data used in this model preparation is the made-up data so the performance of the model may suffer:

- SO3 (%) may come from varying sources, raw material, fuel or alternative fuels.

- FCao (%) is the amount of unreacted free lime left after complete formation of clinker phases.

- AS is alumina modulus.

- SM is the silica modulus

- LS is lime saturation

- C3S, C2S, C3A and C4AF are described above.

- BMSO3 (%) is Ball Mill SO3 that comes from adding as required amount of gypsum needed for setting cement.

- Blaine (m2·kg−1) is the fineness of the cement. 

- R45 (%) is the residue obtained after sieving cement on 45 microns sieve.

- 1D (MPa) (TARGET VARIABLE) is the compressive strength of cement measured after 24 hours for mortar preparation- basically read as 1-day strength. 

Steps performed:
(1)	EDA is done over data.
(2)	Some visualisation is made consisting of all the columns with target variable.
(3)	Outliers were identified and eliminated
(4)	Linear regression is performed 

Outcome:
	R2 value comes out to be 0.44, model didn’t perform well so to improve it assumptions of linear regression can be checked along with some other regression models. 

