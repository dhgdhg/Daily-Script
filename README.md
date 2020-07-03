# Daily Script

### Setting
- `pip install -r `
- 使用@outlook.com, @hotmail.com等smtp服务器为: smtp.live.com的邮箱作为发件邮箱
- edit setting.json and set:
    ```
    "sender": "xxx@hotmail.com",
    "receiver": "xxx@hotmail.com, xxx@hotmail.com",
    "copy_to": "xxx@hotmail.com, xxx@hotmail.com",
    "password": "邮箱密码",
    "subject_template": "【工作日报】XXX_XXX开发组工作日报_{name}_{today}，请查阅，谢谢",
    "name_and_job_number": "姓名 工号",
    "group": "XXXX组",
    "title": "XXX开发项目组工作日报",
    ```
### Usage
- edit setting.json and set:
    ```
    "换行使用": "\n",
    "target": "1. 工作/学习目标\n2. 工作/学习目标",
    "progress": "1. 总体进展 -- 70%",
    "today_process": "1. 今日进展\n2. 今日进展",
    "risk": "风险及问题",
    "plan": "明日计划"
    ```
- send:
    - `python3 send.py` 或 `chmod u+x send.py;./send.py`
    