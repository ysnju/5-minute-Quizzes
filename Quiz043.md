kivy.md code
```.md
ScreenManager:
    id: scr_manager

    LoginScreen:
        name: "LoginScreen"
    MainScreen:
        name:"MainScreen"
    NewitemScreen:
        name:"NewitemScreen"

<LoginScreen>:
    BoxLayout:
        orientation: 'vertical'
        size: 200,500
    MDCard:
        size: 200, 500
        pos_hint:{"center_x":.5,"center_y":.5}
        #hint is in relatio

        MDRaisedButton:
            id: red_btn
            size_hint: .2, 1
            text: "log in"
            font_size: "30px"
            #RGB code
            md_bg_color: 1, 0, 0, 1
            on_release:
                root.current = "MainScreen"
<MainScreen>:
    BoxLayout:
        orientation: 'vertical'
        size: 200,500
    MDCard:
        size: 200, 500
        pos_hint:{"center_x":.5,"center_y":.5}
        #hint is in relatio

        MDRaisedButton:
            id: red_btn
            size_hint: .2, 1
            text: "New"
            font_size: "30px"
            #RGB code
            md_bg_color: 1, 0, 0, 1
            on_release:
                root.current = "NewitemScreen"

        MDRaisedButton:
            id: red_btn
            size_hint: .2, 1
            text: "List"
            font_size: "30px"
            #RGB code
            md_bg_color: 1, 0, 0, 1



        MDRaisedButton:
            id: red_btn
            size_hint: .2, 1
            text: "log out"
            font_size: "30px"
            #RGB code
            md_bg_color: 1, 0, 0, 1
            on_release:
                root.current = "LoginScreen"

<NewitemScreen>:
    BoxLayout:
        orientation: 'vertical'
        size: 200,500
    MDCard:
        size: 200, 500
        pos_hint:{"center_x":.5,"center_y":.5}
        #hint is in relatio

        MDRaisedButton:
            id: red_btn
            size_hint: .2, 1
            text: "back"
            font_size: "30px"
            #RGB code
            md_bg_color: 1, 0, 0, 1
            on_release:
                root.parent.current = "MainScreen"
```
python file
```py

from kivymd.app import MDApp
from kivymd.uix.screen import MDScreen

class LoginScreen(MDScreen):
    pass

class MainScreen(MDScreen):
    pass
class NewitemScreen(MDScreen):
    pass
class Quiz043(MDApp):
    def build(self):
        return

m = Quiz043()
m.run()
```
<img width="494" alt="Screenshot 2022-04-18 at 16 37 44" src="https://user-images.githubusercontent.com/89366347/163773971-8a4cf540-a3b7-41aa-938f-1913b68c30eb.png">




https://user-images.githubusercontent.com/89366347/163774391-e09781b8-c218-4f68-87dc-e6af6589241d.mov


