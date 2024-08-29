my_dict = {"Denis": 1990, "Max": 1999}
print(my_dict)
print(my_dict ["Denis"])

my_dict.update({"Pasha": 2001,
                "Ylyana": 2007})
print(my_dict)

del my_dict["Denis"]
print(my_dict)

# перехожу к множеству

my_set = {1, 1, 1, 2, 3, 4, 4, 5,}
print(my_set)

my_set = {1, 1, 1, 2, 3, 4, 4, 5, "cat", True, (5, 7, 9,)}
print(my_set)
my_face = [1, 2, 1, 1, 2, 3, 3]
my_face = set(my_face)
print(my_face)
print(my_face.discard(3))
print(my_face)

# здесь в конце не понял как правильно сделать
