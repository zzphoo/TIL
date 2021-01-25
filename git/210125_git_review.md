# TIL 20210125_git

## TIL
- review what i learned last week
  check what i made : readme.md open file with VIM
- first commit for review

- Python 4th class

  how to use for, while in python.



for s in "python":
    print('{} for python'.format(s))



animals = ['cat','dog','aligator','tiger','lion']
for animal in animals:
    print('there is {} in cage'.format(animal))



import random

magic_number = random.randint(1,20)
print("stop at ",magic_number)
for i in range(1,100+1):
    if i == magic_number:
        break
    elif i%2==0:   #i다음에 뭔지 모르겠음 배수찾기 %였음!
        print('skip for now')
        continue
    print(i)



lists_in_list = [
    [1, 0, 7, 0],
    [0, 2, 0, 9],
    [0, 6, 3, 7],
    [4, 0, 5, 1],
]

result = 0
for list_ in lists_in_list:
    result += (sum(list_))
    print(result)



##TODO
- after commit, check everythings fine 
- try to change blog theme to 'NEXT'
- make TIL category on blog
