# 🅰️ Angular Tutorials & Masterclass

Welcome to the **Angular Tutorials** repository! This repository contains structured, step-by-step documentation and hands-on guides covering Angular fundamentals, modern component architecture, template syntax, signals, and application building blocks.

All tutorial modules are cross-referenced and strictly verified against the official Angular documentation ([angular.dev](https://angular.dev)).

---

## 📚 Curriculum & Topics Overview

| Module | Topic Title | Key Concepts Covered | Official References |
| :--- | :--- | :--- | :--- |
| [**Module 01**](file:///home/abanoub/Desktop/projects/Angular_Tutorials/01_introduction_and_boot_flow.md) | [01. Introduction & Application Boot Flow](file:///home/abanoub/Desktop/projects/Angular_Tutorials/01_introduction_and_boot_flow.md) | • What is Angular?<br>• Framework vs. Library (Inversion of Control)<br>• Single Page Applications (SPA)<br>• Angular CLI Basics (`ng new`, `ng serve`, `ng g`)<br>• Standalone Components vs. `NgModule`<br>• Step-by-Step Boot Flow (`main.ts` $\rightarrow$ `bootstrapApplication`) | [angular.dev/overview](https://angular.dev/overview)<br>[angular.dev/tools/cli](https://angular.dev/tools/cli) |
| [**Module 02**](file:///home/abanoub/Desktop/projects/Angular_Tutorials/02_decorators_and_data_binding.md) | [02. Decorators & Data Binding](file:///home/abanoub/Desktop/projects/Angular_Tutorials/02_decorators_and_data_binding.md) | • Angular Decorators (`@Component`, `@Directive`, `@Pipe`, `@Injectable`, `@Input`, `@Output`)<br>• Data Binding directions (Source $\rightarrow$ View, View $\rightarrow$ Source, Two-Way)<br>• Interpolation `{{ }}` & Signals<br>• Property `[prop]`, Attribute `[attr.x]`, Class `[class.x]`, Style `[style.x]`, ARIA bindings<br>• Event Binding `(event)` & Key Modifiers (`keyup.enter`)<br>• Two-Way Data Binding (`[(ngModel)]` & Signal `model()`) | [angular.dev/guide/templates/binding](https://angular.dev/guide/templates/binding)<br>[angular.dev/guide/templates/two-way-binding](https://angular.dev/guide/templates/two-way-binding) |

---

## 🛠️ Prerequisites & Local Setup

### 1. Requirements
- **Node.js**: v18.13.0 or higher
- **npm**: v9.0.0 or higher
- **Angular CLI**: Latest version

### 2. Angular CLI Setup
```bash
# Install Angular CLI globally
npm install -g @angular/cli

# Verify installation
ng version
```

### 3. Creating & Running a New Angular App
```bash
# Create a new Angular app with default Standalone component setup
ng new my-angular-app

# Navigate into the project directory
cd my-angular-app

# Start the local development server
ng serve -o
```

---

## 🌐 Official Documentation & Resources

- 📖 **Official Angular Documentation:** [angular.dev](https://angular.dev)
- 🚀 **Angular CLI Reference:** [angular.dev/tools/cli](https://angular.dev/tools/cli)
- 💡 **Interactive Tutorials:** [angular.dev/tutorials](https://angular.dev/tutorials)