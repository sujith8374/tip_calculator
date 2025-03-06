# tip_calculator
print( "welcome to the tip calculator" )
bill = float(input("what was the total bill"))
tip = int(input("what percentage tip whould you like to give? 12 14 16"))
people = int(input("how many people want to share?"))
tip_as_per = tip / 100
total_tip_amount = bill * tip_as_per
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round (bill_per_person )
print(f"your total amount is {final_amount}")
