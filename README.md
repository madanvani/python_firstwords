# python_firstwords
python_first-word-letters



username=input()
length=len(username)
last_index=int(length)-int(length/12)
first_index=username[:last_index]
print(first_index)
