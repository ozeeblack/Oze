form request import post
print("code by Ozeeblack")
i = input ( masukan no : )
dat = ('msisdn' : i)
re=post (https:roli.telkomsel.com/auth/forgot_password',dat)
print("STATUS : " re.json()["message"])
