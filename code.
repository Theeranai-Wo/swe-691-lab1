def calculate_grade(scores): 
    # 1. ป้องกัน ZeroDivisionError ด้วยการตรวจสอบลิสต์ว่าง
    if not scores: 
        return "N/A", 0.0 

    # 2. ปรับปรุงให้เป็น Pythonic Style ด้วยการใช้ sum() ช่วยเพิ่มความเร็ว
    total = sum(scores) 
    average = total / len(scores) 
    
    if average >= 80: 
        grade = "A" 
    elif average >= 70: 
        grade = "B" 
    elif average >= 60: 
        grade = "C" 
    elif average >= 50: 
        grade = "D" 
    else: 
        grade = "F" 
        
    return grade, average 

# ตัวอย่างการใช้งาน
scores = [85, 92, 78, 88, 95] 
print(calculate_grade(scores))
