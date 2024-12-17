[Housing Prices Competition for Kaggle Learn Users](https://www.kaggle.com/competitions/home-data-for-ml-course/overview)

# The data has been split into two groups:
* train.csv - the training set
* test.csv - the test set

# Data Dictionary

## MSSubClass
Identifies the type of dwelling involved in the sale.

| Code | Description                              |
|------|------------------------------------------|
| 20   | 1-STORY 1946 & NEWER ALL STYLES          |
| 30   | 1-STORY 1945 & OLDER                     |
| 40   | 1-STORY W/FINISHED ATTIC ALL AGES        |
| 45   | 1-1/2 STORY - UNFINISHED ALL AGES        |
| 50   | 1-1/2 STORY FINISHED ALL AGES            |
| 60   | 2-STORY 1946 & NEWER                     |
| 70   | 2-STORY 1945 & OLDER                     |
| 75   | 2-1/2 STORY ALL AGES                     |
| 80   | SPLIT OR MULTI-LEVEL                     |
| 85   | SPLIT FOYER                              |
| 90   | DUPLEX - ALL STYLES AND AGES             |
| 120  | 1-STORY PUD (1946 & NEWER)               |
| 150  | 1-1/2 STORY PUD - ALL AGES               |
| 160  | 2-STORY PUD (1946 & NEWER)               |
| 180  | PUD - MULTILEVEL                         |
| 190  | 2 FAMILY CONVERSION - ALL AGES           |

---

## MSZoning
Identifies the general zoning classification of the sale.

| Code | Description                     |
|------|---------------------------------|
| A    | Agriculture                     |
| C    | Commercial                      |
| FV   | Floating Village Residential    |
| I    | Industrial                      |
| RH   | Residential High Density        |
| RL   | Residential Low Density         |
| RP   | Residential Low Density Park    |
| RM   | Residential Medium Density      |

---

## LotFrontage
Linear feet of street connected to property.

## LotArea
Lot size in square feet.

---

## Street
Type of road access to property.

| Code | Description |
|------|-------------|
| Grvl | Gravel      |
| Pave | Paved       |

---

## Alley
Type of alley access to property.

| Code | Description     |
|------|-----------------|
| Grvl | Gravel          |
| Pave | Paved           |
| NA   | No alley access |

---

## LotShape
General shape of property.

| Code | Description             |
|------|-------------------------|
| Reg  | Regular                 |
| IR1  | Slightly irregular      |
| IR2  | Moderately Irregular    |
| IR3  | Irregular               |

---

## LandContour
Flatness of the property.

| Code | Description                                  |
|------|---------------------------------------------|
| Lvl  | Near Flat/Level                             |
| Bnk  | Banked - Quick rise from street grade       |
| HLS  | Hillside - Significant slope side to side   |
| Low  | Depression                                  |

---

## Utilities
Type of utilities available.

| Code   | Description                                |
|--------|--------------------------------------------|
| AllPub | All public utilities (Electric, Gas, Water, Sewer) |
| NoSewr | Electricity, Gas, and Water (Septic Tank)  |
| NoSeWa | Electricity and Gas Only                  |
| ELO    | Electricity only                          |

---

## LotConfig
Lot configuration.

| Code     | Description                  |
|----------|------------------------------|
| Inside   | Inside lot                   |
| Corner   | Corner lot                   |
| CulDSac  | Cul-de-sac                   |
| FR2      | Frontage on 2 sides of lot   |
| FR3      | Frontage on 3 sides of lot   |

---

## LandSlope
Slope of the property.

| Code | Description        |
|------|--------------------|
| Gtl  | Gentle slope       |
| Mod  | Moderate slope     |
| Sev  | Severe slope       |

---

## Neighborhood
Physical locations within Ames city limits.

| Code      | Description              |
|-----------|--------------------------|
| Blmngtn   | Bloomington Heights      |
| Blueste   | Bluestem                 |
| BrDale    | Briardale                |
| BrkSide   | Brookside                |
| ClearCr   | Clear Creek              |
| CollgCr   | College Creek            |
| Crawfor   | Crawford                 |
| Edwards   | Edwards                  |
| Gilbert   | Gilbert                  |
| IDOTRR    | Iowa DOT and Rail Road   |
| MeadowV   | Meadow Village           |
| Mitchel   | Mitchell                 |
| Names     | North Ames               |
| NoRidge   | Northridge               |
| NPkVill   | Northpark Villa          |
| NridgHt   | Northridge Heights       |
| NWAmes    | Northwest Ames           |
| OldTown   | Old Town                 |
| SWISU     | South & West of ISU      |
| Sawyer    | Sawyer                   |
| SawyerW   | Sawyer West              |
| Somerst   | Somerset                 |
| StoneBr   | Stone Brook              |
| Timber    | Timberland               |
| Veenker   | Veenker                  |

---

## Condition1 & Condition2
Proximity to various conditions.

| Code  | Description                             |
|-------|-----------------------------------------|
| Artery| Adjacent to arterial street             |
| Feedr | Adjacent to feeder street               |
| Norm  | Normal                                  |
| RRNn  | Within 200' of North-South Railroad     |
| RRAn  | Adjacent to North-South Railroad        |
| PosN  | Near positive feature (e.g. park)       |
| PosA  | Adjacent to positive feature            |
| RRNe  | Within 200' of East-West Railroad       |
| RRAe  | Adjacent to East-West Railroad          |

---

## BldgType
Type of dwelling.

| Code    | Description                               |
|---------|-------------------------------------------|
| 1Fam    | Single-family Detached                    |
| 2FmCon  | Two-family Conversion                    |
| Duplx   | Duplex                                   |
| TwnhsE  | Townhouse End Unit                       |
| TwnhsI  | Townhouse Inside Unit                    |

---

## HouseStyle
Style of dwelling.

| Code    | Description                                 |
|---------|---------------------------------------------|
| 1Story  | One story                                  |
| 1.5Fin  | One and one-half story: 2nd level finished |
| 1.5Unf  | One and one-half story: 2nd level unfinished|
| 2Story  | Two story                                  |
| 2.5Fin  | Two and one-half story: 2nd level finished |
| 2.5Unf  | Two and one-half story: 2nd level unfinished|
| SFoyer  | Split Foyer                                |
| SLvl    | Split Level                                |

---

## OverallQual
Rates the overall material and finish of the house.

| Code | Rating         |
|------|----------------|
| 10   | Very Excellent |
| 9    | Excellent      |
| 8    | Very Good      |
| 7    | Good           |
| 6    | Above Average  |
| 5    | Average        |
| 4    | Below Average  |
| 3    | Fair           |
| 2    | Poor           |
| 1    | Very Poor      |

---

## OverallCond
Rates the overall condition of the house.

| Code | Rating         |
|------|----------------|
| 10   | Very Excellent |
| 9    | Excellent      |
| 8    | Very Good      |
| 7    | Good           |
| 6    | Above Average  |
| 5    | Average        |
| 4    | Below Average  |
| 3    | Fair           |
| 2    | Poor           |
| 1    | Very Poor      |

---

## YearBuilt
Original construction date.

## YearRemodAdd
Remodel date (same as construction date if no remodeling or additions).

---

## RoofStyle
Type of roof.

| Code    | Description      |
|---------|------------------|
| Flat    | Flat             |
| Gable   | Gable            |
| Gambrel | Gabrel (Barn)    |
| Hip     | Hip              |
| Mansard | Mansard          |
| Shed    | Shed             |

---

## RoofMatl
Roof material.

| Code    | Description                   |
|---------|-------------------------------|
| ClyTile | Clay or Tile                  |
| CompShg | Standard (Composite) Shingle  |
| Membran | Membrane                      |
| Metal   | Metal                         |
| Roll    | Roll                          |
| Tar&Grv | Gravel & Tar                  |
| WdShake | Wood Shakes                   |
| WdShngl | Wood Shingles                 |

---

## Exterior1st
Exterior covering on the house.

| Code     | Description            |
|----------|------------------------|
| AsbShng  | Asbestos Shingles      |
| AsphShn  | Asphalt Shingles       |
| BrkComm  | Brick Common           |
| BrkFace  | Brick Face             |
| CBlock   | Cinder Block           |
| CemntBd  | Cement Board           |
| HdBoard  | Hard Board             |
| ImStucc  | Imitation Stucco       |
| MetalSd  | Metal Siding           |
| Other    | Other                  |
| Plywood  | Plywood                |
| PreCast  | PreCast                |
| Stone    | Stone                  |
| Stucco   | Stucco                 |
| VinylSd  | Vinyl Siding           |
| Wd Sdng  | Wood Siding            |
| WdShing  | Wood Shingles          |

---

## Exterior2nd
Exterior covering on the house (if more than one material).

| Code     | Description            |
|----------|------------------------|
| AsbShng  | Asbestos Shingles      |
| AsphShn  | Asphalt Shingles       |
| BrkComm  | Brick Common           |
| BrkFace  | Brick Face             |
| CBlock   | Cinder Block           |
| CemntBd  | Cement Board           |
| HdBoard  | Hard Board             |
| ImStucc  | Imitation Stucco       |
| MetalSd  | Metal Siding           |
| Other    | Other                  |
| Plywood  | Plywood                |
| PreCast  | PreCast                |
| Stone    | Stone                  |
| Stucco   | Stucco                 |
| VinylSd  | Vinyl Siding           |
| Wd Sdng  | Wood Siding            |
| WdShing  | Wood Shingles          |

---

## MasVnrType
Masonry veneer type.

| Code    | Description       |
|---------|-------------------|
| BrkCmn  | Brick Common      |
| BrkFace | Brick Face        |
| CBlock  | Cinder Block      |
| None    | None              |
| Stone   | Stone             |

---

## MasVnrArea
Masonry veneer area in square feet.

---

## ExterQual
Evaluates the quality of the material on the exterior.

| Code | Description         |
|------|---------------------|
| Ex   | Excellent           |
| Gd   | Good                |
| TA   | Average/Typical     |
| Fa   | Fair                |
| Po   | Poor                |

---

## ExterCond
Evaluates the present condition of the material on the exterior.

| Code | Description         |
|------|---------------------|
| Ex   | Excellent           |
| Gd   | Good                |
| TA   | Average/Typical     |
| Fa   | Fair                |
| Po   | Poor                |

---

## Foundation
Type of foundation.

| Code    | Description        |
|---------|--------------------|
| BrkTil  | Brick & Tile       |
| CBlock  | Cinder Block       |
| PConc   | Poured Concrete    |
| Slab    | Slab               |
| Stone   | Stone              |
| Wood    | Wood               |

---

## BsmtQual
Evaluates the height of the basement.

| Code | Description                |
|------|----------------------------|
| Ex   | Excellent (100+ inches)    |
| Gd   | Good (90-99 inches)        |
| TA   | Typical (80-89 inches)     |
| Fa   | Fair (70-79 inches)        |
| Po   | Poor (<70 inches)          |
| NA   | No Basement                |

---

## BsmtCond
Evaluates the general condition of the basement.

| Code | Description                                      |
|------|--------------------------------------------------|
| Ex   | Excellent                                       |
| Gd   | Good                                            |
| TA   | Typical - slight dampness allowed               |
| Fa   | Fair - dampness or some cracking or settling    |
| Po   | Poor - Severe cracking, settling, or wetness    |
| NA   | No Basement                                     |

---

## BsmtExposure
Refers to walkout or garden level walls.

| Code | Description                                       |
|------|---------------------------------------------------|
| Gd   | Good Exposure                                    |
| Av   | Average Exposure (split levels/foyers score well)|
| Mn   | Minimum Exposure                                 |
| No   | No Exposure                                      |
| NA   | No Basement                                      |

---

## BsmtFinType1
Rating of basement finished area.

| Code | Description                   |
|------|-------------------------------|
| GLQ  | Good Living Quarters          |
| ALQ  | Average Living Quarters       |
| BLQ  | Below Average Living Quarters |
| Rec  | Average Rec Room              |
| LwQ  | Low Quality                   |
| Unf  | Unfinished                    |
| NA   | No Basement                   |

---

## BsmtFinSF1
Type 1 finished square feet.

---

## BsmtFinType2
Rating of basement finished area (if multiple types).

| Code | Description                   |
|------|-------------------------------|
| GLQ  | Good Living Quarters          |
| ALQ  | Average Living Quarters       |
| BLQ  | Below Average Living Quarters |
| Rec  | Average Rec Room              |
| LwQ  | Low Quality                   |
| Unf  | Unfinished                    |
| NA   | No Basement                   |

---

## BsmtFinSF2
Type 2 finished square feet.

---

## BsmtUnfSF
Unfinished square feet of basement area.

---

## TotalBsmtSF
Total square feet of basement area.

---

## Heating
Type of heating.

| Code  | Description                       |
|-------|-----------------------------------|
| Floor | Floor Furnace                     |
| GasA  | Gas forced warm air furnace       |
| GasW  | Gas hot water or steam heat       |
| Grav  | Gravity furnace                   |
| OthW  | Hot water or steam heat (non-gas) |
| Wall  | Wall furnace                      |

---

## HeatingQC
Heating quality and condition.

| Code | Description         |
|------|---------------------|
| Ex   | Excellent           |
| Gd   | Good                |
| TA   | Average/Typical     |
| Fa   | Fair                |
| Po   | Poor                |

---

## CentralAir
Central air conditioning.

| Code | Description |
|------|-------------|
| N    | No          |
| Y    | Yes         |

---

## Electrical
Electrical system.

| Code   | Description                                          |
|--------|------------------------------------------------------|
| SBrkr  | Standard Circuit Breakers & Romex                    |
| FuseA  | Fuse Box over 60 AMP and all Romex wiring (Average)  |
| FuseF  | 60 AMP Fuse Box and mostly Romex wiring (Fair)       |
| FuseP  | 60 AMP Fuse Box and mostly knob & tube wiring (Poor) |
| Mix    | Mixed                                                |

---

## 1stFlrSF
First Floor square feet.

## 2ndFlrSF
Second Floor square feet.

## LowQualFinSF
Low quality finished square feet (all floors).

## GrLivArea
Above grade (ground) living area square feet.

---

## BsmtFullBath
Basement full bathrooms.

## BsmtHalfBath
Basement half bathrooms.

## FullBath
Full bathrooms above grade.

## HalfBath
Half bathrooms above grade.

---

## Bedroom
Bedrooms above grade (does NOT include basement bedrooms).

## Kitchen
Kitchens above grade.

## KitchenQual
Kitchen quality.

| Code | Description         |
|------|---------------------|
| Ex   | Excellent           |
| Gd   | Good                |
| TA   | Typical/Average     |
| Fa   | Fair                |
| Po   | Poor                |

---

## TotRmsAbvGrd
Total rooms above grade (does not include bathrooms).

---

## Functional
Home functionality (Assume typical unless deductions apply).

| Code  | Description            |
|-------|------------------------|
| Typ   | Typical Functionality  |
| Min1  | Minor Deductions 1     |
| Min2  | Minor Deductions 2     |
| Mod   | Moderate Deductions    |
| Maj1  | Major Deductions 1     |
| Maj2  | Major Deductions 2     |
| Sev   | Severely Damaged       |
| Sal   | Salvage only           |

---

## Fireplaces
Number of fireplaces.

## FireplaceQu
Fireplace quality.

| Code | Description                                |
|------|--------------------------------------------|
| Ex   | Excellent - Exceptional Masonry Fireplace  |
| Gd   | Good - Masonry Fireplace in main level     |
| TA   | Average - Prefabricated/Masonry (basement) |
| Fa   | Fair - Prefabricated (basement)            |
| Po   | Poor - Ben Franklin Stove                  |
| NA   | No Fireplace                               |

---

## GarageType
Garage location.

| Code    | Description                                     |
|---------|-------------------------------------------------|
| 2Types  | More than one type of garage                   |
| Attchd  | Attached to home                               |
| Basment | Basement Garage                                |
| BuiltIn | Built-In (room above garage)                   |
| CarPort | Car Port                                       |
| Detchd  | Detached from home                             |
| NA      | No Garage                                      |

---

## GarageYrBlt
Year garage was built.

## GarageFinish
Interior finish of the garage.

| Code | Description      |
|------|------------------|
| Fin  | Finished         |
| RFn  | Rough Finished   |
| Unf  | Unfinished       |
| NA   | No Garage        |

---

## GarageCars
Size of garage in car capacity.

## GarageArea
Size of garage in square feet.

## GarageQual  
**Garage quality.**

| Code | Description      |
|------|------------------|
| Ex   | Excellent        |
| Gd   | Good             |
| TA   | Typical/Average  |
| Fa   | Fair             |
| Po   | Poor             |
| NA   | No Garage        |

---

## GarageCond  
**Garage condition.**

| Code | Description      |
|------|------------------|
| Ex   | Excellent        |
| Gd   | Good             |
| TA   | Typical/Average  |
| Fa   | Fair             |
| Po   | Poor             |
| NA   | No Garage        |

---

## PavedDrive  
**Paved driveway.**

| Code | Description       |
|------|-------------------|
| Y    | Paved             |
| P    | Partial Pavement  |
| N    | Dirt/Gravel       |

---

## WoodDeckSF  
**Wood deck area in square feet.**  

## OpenPorchSF  
**Open porch area in square feet.**  

## EnclosedPorch  
**Enclosed porch area in square feet.**  

## 3SsnPorch  
**Three season porch area in square feet.**  

## ScreenPorch  
**Screen porch area in square feet.**  

---

## PoolArea  
**Pool area in square feet.**

## PoolQC  
**Pool quality.**

| Code | Description      |
|------|------------------|
| Ex   | Excellent        |
| Gd   | Good             |
| TA   | Average/Typical  |
| Fa   | Fair             |
| NA   | No Pool          |

---

## Fence  
**Fence quality.**

| Code  | Description          |
|-------|----------------------|
| GdPrv | Good Privacy         |
| MnPrv | Minimum Privacy      |
| GdWo  | Good Wood            |
| MnWw  | Minimum Wood/Wire    |
| NA    | No Fence             |

---

## MiscFeature  
**Miscellaneous feature not covered in other categories.**

| Code  | Description                                 |
|-------|---------------------------------------------|
| Elev  | Elevator                                   |
| Gar2  | 2nd Garage (if not described in garage section) |
| Othr  | Other                                      |
| Shed  | Shed (over 100 SF)                         |
| TenC  | Tennis Court                               |
| NA    | None                                       |

---

## MiscVal  
**Dollar value of miscellaneous feature.**

---

## MoSold  
**Month Sold (MM).**

## YrSold  
**Year Sold (YYYY).**

---

## SaleType  
**Type of sale.**

| Code  | Description                                   |
|-------|-----------------------------------------------|
| WD    | Warranty Deed - Conventional                 |
| CWD   | Warranty Deed - Cash                         |
| VWD   | Warranty Deed - VA Loan                      |
| New   | Home just constructed and sold               |
| COD   | Court Officer Deed/Estate                    |
| Con   | Contract 15% Down payment regular terms      |
| ConLw | Contract Low Down payment and low interest   |
| ConLI | Contract Low Interest                        |
| ConLD | Contract Low Down                            |
| Oth   | Other                                        |

---

## SaleCondition  
**Condition of sale.**

| Code    | Description                                                           |
|---------|-----------------------------------------------------------------------|
| Normal  | Normal Sale                                                           |
| Abnorml | Abnormal Sale - trade, foreclosure, short sale                        |
| AdjLand | Adjoining Land Purchase                                               |
| Alloca  | Allocation - two linked properties with separate deeds, typically condos |
| Family  | Sale between family members                                           |
| Partial | Home not completed when last assessed (associated with New Homes)     |