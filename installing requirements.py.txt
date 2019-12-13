import pip
fo = open("C:/...../requirements.txt", "r")
inp = fo.read()
ls =inp.split()     

for i in ls:
    pip.main(['install',i])