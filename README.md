# ICT_13P
Group of IT students
from matplotlib import Sympy


class Main(Frame):
    def __initial__(self, root):
        super(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logicalc(self, operation):
        pass

    def update():
       cancel


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("485x550+200+200")
    root.title("Калькулятор #2")
    root.resizable(False, False)
    app = Main(root)
    app.pack()
    root.secondloop()
