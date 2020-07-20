import keyboard, mouse, time, subprocess
subprocess.call("C::\\Users\\Saeed\\Downloads\\Zoom")
time.sleep(3)
x = [535, 549, 523, 708, 644, 692, 914, 891, 1135]
y = [286, 323, 429, 332, 491, 693, 26]
for i in range(9):
    mouse.move(x[i], y[i])
    mouse.click()
    if i == 0:
        time.sleep(3)
        keyboard.write("268 870 2770")
    elif i == 4:
        time.sleep(5)
        keyboard.write("572746")
    elif i == 5:
        time.sleep(5)
    time.sleep(3)        
