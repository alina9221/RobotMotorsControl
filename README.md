class RobotMotor:
    def __init__(self, name):
        self.name = name
        self.speed = 0

    def set_speed(self, speed):
        self.speed = speed
        print(f"Мотор {self.name}: скорость установлена на {self.speed}%")

# Пример использования
if __name__ == "__main__":
    left_motor = RobotMotor("Левый")
    right_motor = RobotMotor("Правый")

    left_motor.set_speed(50)
    right_motor.set_speed(50)
