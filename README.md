# foundation-assignment
#An undisturbed sample of clay 24mm thick consolidated 50% in 20 minutes when tested in the laboratory, with drainage allowed at the top and bottom. The clay layer from which the sample was obtained is 4m tick in the field. How much time will it take place to consolidate 50% with a single drain?

# Given values
t_lab = 20  # Time for 50% consolidation in the lab (in minutes)
H_lab = 0.024  # Thickness of the lab sample (in meters)
H_field = 4  # Thickness of the field clay layer (in meters)

# Calculate time for 50% consolidation in the field using the formula
t_field = t_lab * (H_field / H_lab) ** 2

# Convert time from minutes to hours and days
t_field_hours = t_field / 60
t_field_days = t_field_hours / 24

# Display results
print(f"Time for 50% consolidation in the field: {t_field:.2f} minutes")
print(f"Time for 50% consolidation in the field: {t_field_hours:.2f} hours")
print(f"Time for 50% consolidation in the field: {t_field_days:.2f} days")
