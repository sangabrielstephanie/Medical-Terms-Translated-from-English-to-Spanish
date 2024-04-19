# Medical-Terms-Translated-from-English-to-Spanish
englishphraselist = ["Open your eyes", "Point to where it hurts", "Breath slowly", "You need to exercise more", "You need to do these tests", "Turn your head and cough", "Lift your head", "Open your mouth", "I’m going to examine your nose", "I’m going to listen to your heart", "Please lie down", "I have finished the exam", "doctor", "nurse", "Hospital", "insurance", "emergency room", "infection", "surgery", "anesthesia", "blood", "medicine", "lab", "pain", "fever", "to cough"]

print("THESE ARE THE TERMS THAT CAN BE TRANSLATED : ")
for x in englishphraselist :
    print(x)

def result(englishphrase): 
        if englishphrase == 'Open your eyes':
           return 'Abra los ojos'
        elif englishphrase == 'Point to where it hurts':
           return 'Señale donde le duele'
        elif englishphrase == 'Breath slowly':
           return 'Respire lentamente'
        elif englishphrase == 'You need to exercise more':
           return 'Necesita hacer mas ejercicio'
        elif englishphrase == 'You need to exercise':
           return 'Necesita hacer más ejercicio'
        elif englishphrase == 'You need to do these tests.':
           return 'Tiene que hacerse estos análisis'
        elif englishphrase == 'Turn your head and cough':
           return 'Volte la cabeza y tosa'
        elif englishphrase == 'I’m going to examine your nose':
           return 'Voy a examinar su nariz.'
        elif englishphrase == 'I am going to listen to your heart':
           return 'Voy a escuchar su corazón'
        elif englishphrase == 'Please lie down':
           return 'Acuéstese por favor'
        elif englishphrase == 'I have finished the exam':
           return 'Terminé la examinación'
        elif englishphrase == 'Doctor':
           return ' el doctor / la doctora'
        elif englishphrase == 'Nurse':
           return 'el enfermero /la enfermera'
        elif englishphrase == 'hospital':
           return 'el hospital'
        elif englishphrase == 'insurance':
           return 'el seguro'
        elif englishphrase == 'emergency':
           return 'la sala de emergencia'
        elif englishphrase == 'infection':
           return 'la infección'
        elif englishphrase == 'surgery':
           return 'la cirugía'
        elif englishphrase == 'anesthesia':
           return 'la anestesia'
        elif englishphrase == 'blood':
           return 'la sangre'
        elif englishphrase == 'medicine':
           return 'la medicina'
        elif englishphrase == 'lab':
           return 'el laboratorio'
        elif englishphrase == 'pain':
           return 'el dolor'
        elif englishphrase == 'fever':
           return 'la fiebre'
        elif englishphrase == 'to cough':
           return 'toser'
        else:
           return None


def main():
    print("WHAT MEDICAL TERM WOULD YOU LIKE TRANSLATED?")
    englishphrase = input("Enter English medical term: ")
    spanishphrase = result(englishphrase)
    if spanishphrase is not None:
        print("The phrase", englishphrase, "belongs to the phrase", spanishphrase)
    else:
        print("Translation not available for the phrase", englishphrase)

if __name__ == "__main__":
    main()
