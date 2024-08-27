import time

def countdown(minutes):
    seconds = minutes * 60
    while seconds:
        mins, secs = divmod(seconds, 60)
        timer = '{:02d}:{:02d}'.format(mins, secs)
        print(timer, end="\r")
        time.sleep(1)
        seconds -= 1
    print("时间到！")

def main():
    try:
        focus_time = int(input("请输入专注时间（分钟）："))
        print(f"开始专注 {focus_time} 分钟")
        countdown(focus_time)
    except ValueError:
        print("请输入有效的数字")

if __name__ == "__main__":
    main()
