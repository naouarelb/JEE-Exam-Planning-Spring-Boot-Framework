# 📚 Exam Scheduling with Spring Boot

An application for **exam management and scheduling** built with the **Spring Boot** framework.  
It allows efficient organization of exams, rooms, invigilators, and related logistics.

---

## 🚀 Introduction
This application provides complete exam management with features such as:  
- Creating, updating, and deleting exams  
- Managing rooms, invigilators, and absence controllers  
- Viewing exam details and generating official documents (reports, transcripts, attendance sheets)  

---

## 🛠️ Prerequisites
Before getting started, make sure you have:  
- **Java JDK** 11 or higher  
- **Maven**  
- **IDE** (IntelliJ IDEA, Eclipse, etc.)  
- **PostgreSQL** (or any other DB supported by Spring Data JPA — update `application.properties` accordingly)  

---

## Architecture
![Architecture](images/Architecture.drawio.png)


## ⚡ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/naouarelb/JEE_exams_planning_with_spring_boot.git
```

### 2️⃣ Configure the database
```bash
spring.datasource.url=jdbc:votreSGBD://host:port/NomDB
spring.datasource.username=yourUsername
spring.datasource.password=yourPassword
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Build the application
```bash
mvn clean install
```
### 4️⃣ Run the application
```bash
mvn spring-boot:run
```
## ✨ Features
### ➕ Add an exam
![Ajout d'un examen](images/formulaire_Creation_Examen.png)

### ❌ Delete an exam

### ✏️ Update exam details
![Modification d'un examen](images/formulaire_Modification_Examen.png)

### 🏫 Assign rooms
👨‍🏫 Assign invigilators and absence controllers
![Affectation des salles](images/Affectation_Salles.png)

### 📄 View exam information
![Consultation](images/infomation.png)

### 📝 Generate official documents: reports, transcripts, and attendance sheets
![Papier](images/PV_Papport_enonce.png)


## 🤝 Contribution
Contributions are welcome!
Feel free to open an issue or submit a pull request.

### 👤 Author
Naouar EL BOUMASHOULI
