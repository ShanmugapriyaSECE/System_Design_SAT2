# System Design SAT

A Java Maven project scaffold for the System Design SAT repository.

## Requirements
- JDK 17 or later
- Apache Maven 3.8 or later

## Project structure

```text
System-Design-SAT/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/
│   │           └── systemdesignsat/
│   │               └── Main.java
│   └── test/
│       └── java/
├── .gitignore
├── pom.xml
└── README.md
```

## Run

From this folder, run:

```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.systemdesignsat.Main"
```

If Maven's `exec:java` goal is unavailable in your setup, compile and run with your IDE, or add the Maven Exec Plugin to `pom.xml`.

## Push to GitHub

Create an empty repository on GitHub, then run these commands from this folder:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/System-Design-SAT.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and use your repository URL.

> This is a starter scaffold, not a copy of the other repository's source code. Add your actual SAT assignment requirements and implementation before submitting.
