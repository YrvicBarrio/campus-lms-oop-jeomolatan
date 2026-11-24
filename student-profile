class StudentProfile:
    def __init__(self, student_name, student_id):
        self.student_name = student_name
        self.student_id = student_id
        self.__total_score = 0

    def add_points(self, points_earned):
        if points_earned < 0:
            print(ValueError("Cannot add negative points"))

        else:
            self.__total_score = self.__total_score + points_earned


    def get_current_score(self):
        return self.__total_score
