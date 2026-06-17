# Pythonseries
# India Inflation Report (April - June 2026)

india_inflation = {
    "April_2026": {
        "CPI_Inflation": 3.48,
        "Food_Inflation": 4.20,
        "Rural_Inflation": 3.74,
        "Urban_Inflation": 3.16,
        "Status": "Below RBI target"
    },

    "May_2026": {
        "CPI_Inflation": 3.93,
        "Food_Inflation": 4.78,
        "Rural_Inflation": 4.25,
        "Urban_Inflation": 3.53,
        "Status": "Slightly below RBI target"
    },

    "June_2026": {
        "CPI_Inflation": None,
        "Food_Inflation": None,
        "Rural_Inflation": None,
        "Urban_Inflation": None,
        "Status": "Data not released yet"
    }
}

print("INDIA INFLATION REPORT (APRIL-JUNE 2026)")
print("=" * 50)

for month, data in india_inflation.items():
    print(f"\n{month}")
    print("-" * 30)

    for key, value in data.items():
        print(f"{key}: {value}")april_cpi = 3.48
may_cpi = 3.93

increase = may_cpi - april_cpi
percentage_change = (increase / april_cpi) * 100

print(f"April CPI Inflation : {april_cpi}%")
print(f"May CPI Inflation   : {may_cpi}%")
print(f"Increase            : {increase:.2f}%")
print(f"Growth Rate         : {percentage_change:.2f}%")
