from datetime import datetime, timedelta
# Дата последнего приёма кальция ( 14 may)
last_intake_date = datetime.strptime("2023-09-15", "%Y-%m-%d")
# Текущее время
today = datetime.today()

# Разница в днях
days_passed = (today - last_intake_date).days
# Проверка
if days_passed > 200:

    print(f"⚠️ Напоминание: прошло {days_passed} дней с последнего приёма кальция! Пора принять снова.")
else:

    print(f"✅ Всё ок: прошло только {days_passed} дней. Напоминание не требуется.")# take-calcium

    
    ZN
