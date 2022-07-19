# Kaggle-House_Prices_Advanced_Regression_Technique
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

> File descriptions

    1. train.csv - the training set
    2. test.csv - the test set
    3. data_description.txt - full description of each column
    4. sample_submission.csv - a benchmark submission 

> Data fields

    1. SalePrice - the property's sale price in dollars.(target variable)
    2. MSSubClass: The building class
    3. MSZoning: The general zoning classification
    4. LotFrontage: Linear feet of street connected to property
    5. LotArea: Lot size in square feet
    6. Street: Type of road access
    7. Alley: Type of alley access
    8. LotShape: General shape of property
    9. LandContour: Flatness of the property
    10.Utilities: Type of utilities available
    11.LotConfig: Lot configuration
    12.LandSlope: Slope of property
    13.Neighbourhood: Physical locations within Ames city limits
    14.Condition1: Proximity to main road or railroad
    15.Condition2: Proximity to main road or railroad (if a second is present)
    16.BldgType: Type of dwelling
    17.HouseStyle: Style of dwelling
    18.OverallQual: Overall material and finish quality
    19.OverallCond: Overall condition rating
    20.YearBuilt: Original construction date
    21.YearRemodAdd: Remodel date
    22.RoofStyle: Type of roof
    23.RoofMatl: Roof material
    24.Exterior1st: Exterior covering on house
    25.Exterior2nd: Exterior covering on house (if more than one material)
    26.MasVnrType: Masonry veneer type
    27.MasVnrArea: Masonry veneer area in square feet
    28.ExterQual: Exterior material quality
    29.ExterCond: Present condition of the material on the exterior
    30.Foundation: Type of foundation
    31.BsmtQual: Height of the basement
    32.BsmtCond: General condition of the basement
    33.BsmtExposure: Walkout or garden level basement walls
    34.BsmtFinType1: Quality of basement finished area
    35.BsmtFinSF1: Type 1 finished square feet
    BsmtFinType2: Quality of second finished area (if present)
    BsmtFinSF2: Type 2 finished square feet
    BsmtUnfSF: Unfinished square feet of basement area
    TotalBsmtSF: Total square feet of basement area
    Heating: Type of heating
    HeatingQC: Heating quality and condition
    CentralAir: Central air conditioning
    Electrical: Electrical system
    1stFlrSF: First Floor square feet
    2ndFlrSF: Second floor square feet
    LowQualFinSF: Low quality finished square feet (all floors)
    GrLivArea: Above grade (ground) living area square feet
    BsmtFullBath: Basement full bathrooms
    BsmtHalfBath: Basement half bathrooms
    FullBath: Full bathrooms above grade
    HalfBath: Half baths above grade
    Bedroom: Number of bedrooms above basement level
    Kitchen: Number of kitchens
    KitchenQual: Kitchen quality
    TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
    Functional: Home functionality rating
    Fireplaces: Number of fireplaces
    FireplaceQu: Fireplace quality
    GarageType: Garage location
    GarageYrBlt: Year garage was built
    GarageFinish: Interior finish of the garage
    GarageCars: Size of garage in car capacity
    GarageArea: Size of garage in square feet
    GarageQual: Garage quality
    GarageCond: Garage condition
    PavedDrive: Paved driveway
    WoodDeckSF: Wood deck area in square feet
    OpenPorchSF: Open porch area in square feet
    EnclosedPorch: Enclosed porch area in square feet
    3SsnPorch: Three season porch area in square feet
    ScreenPorch: Screen porch area in square feet
    PoolArea: Pool area in square feet
    PoolQC: Pool quality
    Fence: Fence quality
    MiscFeature: Miscellaneous feature not covered in other categories
    MiscVal: $Value of miscellaneous feature
    MoSold: Month Sold
    YrSold: Year Sold
    SaleType: Type of sale
    SaleCondition: Condition of sale
    
   > Metric
   
    Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. 
