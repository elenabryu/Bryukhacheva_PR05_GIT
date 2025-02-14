# **Практическая работа 06**
> ![Изображение](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_eU_1BWOSNZYoNhUCcZlvLvYATkQi77ywSw&s "Я 😍 git")
## **Описание**
Этот проект представляет собой Windows Forms приложение, разработанное на .NET Framework с использованием MS Visual Studio 2019. *Целью проекта* является создание базового приложения Windows Forms с использованием Git для контроля версий и последующей публикации на GitHub и Gitea.
### **Основные этапы реализации:**
* Создание проекта Windows Forms.
* Настройка .gitignore для игнорирования ненужных файлов.
* Инициализация локального репозитория Git.
* Подключение удаленного репозитория на GitHub.
* Создание коммитов с добавлением новой функциональности.
* Публикация проекта на Gitea.
### **Таблица**
| Изменение | Описание |
|-------|----------|
| Новая форма | Добавить новую форму в проект с именем AddForm| 
| ФИО | Добавить Ваше ФИО на главную форму проекта|
|Db.cs |Создать модуль Db.cs со статическим классом.| 
### **Код**  
```
public partial class MainForm : Form
    {
        public MainForm()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            Select select = new Select();
            Hide();
            select.ShowDialog();
            Show();
        }

        private void button2_Click(object sender, EventArgs e)
        {
            Create create = new Create();
            Hide();
            create.ShowDialog(); Show();
            Show();
        }
    }
```
### **Ссылки**
Это я, [elenabryu](https://github.com/elenabryu "Ссылка на мою страницу GitHub")
### *:sparkles:~~Провал~~ Успех! Ваш проект готов к использованию!*:tada:
