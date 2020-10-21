# Hacktober-Fest

*CCA matching personality test*

print("Title of program: CCA Matching Personality test")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

art1 = input("I like to draw and paint.")

uniformgroup1 = input("I want to learn life saving skills")

music1 = input("I can see colours in my mind when i hear music.")

art2 = input("I love colours and admiring pictures and artworks.")

uniformgroup2 = input("I like having a bond with my groupmates.")

music2 = input("I play a musical instrument well.")


art_final = int(art1) + int(art2)
uniformgroup_final = int(uniformgroup1) + int(uniformgroup2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Art Club!")
elif outdoor_final > music_final:
  print("You might be stuiable for St John Brigade!")
else:
  print("You might be suitable for Band!")
