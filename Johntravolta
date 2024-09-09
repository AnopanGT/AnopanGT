def calculate_wage(hours_worked, rate=15000, overtime_rate_multiplier=1.5):
    normal_hours = 40
    if hours_worked <= normal_hours:
        total_wage = hours_worked * rate
    else:
        overtime_hours = hours_worked - normal_hours
        total_wage = (normal_hours * rate) + (overtime_hours * rate * overtime_rate_multiplier)
    return total_wage
    
def calculate_savings(income, expenses=600000):
    if income > expenses:
        savings = income - expenses
        print(f"Bisa menabung, sisa tabungan minggu ini: Rp {savings:,}")
    elif income == expenses:
        print("Tidak bisa menabung")
    else:
        print("Cari tambahan")

# Example
hours_worked = 52
wage = calculate_wage(hours_worked)
print(f"Gaji Mr. John untuk {hours_worked} jam kerja: Rp {wage:,}")

# Example
income = wage  # From the previous calculation
calculate_savings(income)
