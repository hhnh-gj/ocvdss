print("welcome to my computer quiz!")

playing = input("do you want to play? ")

if playing.lower != "yes":
    quit()

print("okay! let's play :)")
score = 0

answer = input("من هو اول نبي ")
if answer.lower =="نبينا ادم عليه السلام"
    print('إجابة صحيحة!')
    score += 1
else:
    print("inocorrect!")

answer = input ("ماهي عاصمة فرنسا ")
if answererer.lower =="باريس"
    print('إجابة صحيحة!')
    score += 1
else:
    print("inocorrect!")

answer = input("ماهوالبحرالذي يفصل بين اوربا وافرقيا؟ ")
if answer.lower =="البحر الابيض المتوسط"
    print('إجابة صحيحة!')
    score += 1
else:
    print("inocorrect!")

answer = input("ماسم بطل مسلسل يركينق بادالذي يتحول من معلم كمياءإلى تاجر مخدرات ")
if answer.lower =="والتر وايت"
    print('إجابة صحيحة!')
    score += 1
else:
    print("inocorrect!")
answer = input("ماهي الدوالة التي تشتهر بإنتاج الشوكلاتة والساعات الفاخرة ؟ ياشقليط ")
if answer.lower =="سويسرا"
    print('إجابة صحيحة!')
    score += 1
else:
    print("inocorrect!")
answer = input("ماهو العنصر الكيميائي الذي يشكل الجزء الاكبر من الكون ويعتبر الوقود الرئيسي للطاقة في النجوم,لكن لم يكتشف حنى الان في حالة نقية على الارض ")
if answer.lower =="الهيدروجين"
    print('إجابة صحيحة!')
else:
    print("inocorrect!")
    score += 1
print("you got " + str(score) + " questons correct!")
print("you got " + str((score / 6) * 100 ) + "%.")
