# 🅰️ Angular Tutorials & Masterclass

Welcome to the **Angular Tutorials** repository! This repository contains structured, step-by-step documentation and hands-on guides covering Angular fundamentals, modern component architecture, template syntax, signals, and application building blocks.

All tutorial modules are strictly verified against the official Angular documentation ([angular.dev](https://angular.dev)).

---

## 📚 Curriculum & Topics Overview

| Module | Topic Title | Key Concepts Covered | Official References |
| :--- | :--- | :--- | :--- |
| [**Module 01**](./01_introduction_and_boot_flow.md) | [01. Introduction & Application Boot Flow](./01_introduction_and_boot_flow.md) | • What is Angular?<br>• Framework vs. Library (Inversion of Control)<br>• Single Page Applications (SPA)<br>• Angular CLI Basics (`ng new`, `ng serve`, `ng g`)<br>• Standalone Components vs. `NgModule`<br>• Step-by-Step Boot Flow (`angular.json` $\rightarrow$ `main.ts` $\rightarrow$ `app.config.ts` $\rightarrow$ `index.html`) | [angular.dev/overview](https://angular.dev/overview)<br>[angular.dev/tools/cli](https://angular.dev/tools/cli) |
| [**Module 02**](./02_decorators_and_data_binding.md) | [02. Decorators & Data Binding](./02_decorators_and_data_binding.md) | • Angular Decorators (`@Component`, `@Directive`, `@Pipe`, `@Injectable`, `@Input`, `@Output`)<br>• Data Binding directions (Source $\rightarrow$ View, View $\rightarrow$ Source, Two-Way)<br>• Interpolation `{{ }}` & Signals<br>• Property `[prop]`, Attribute `[attr.x]`, Class `[class.x]`, Style `[style.x]`, ARIA bindings<br>• Event Binding `(event)` & Key Modifiers (`keyup.enter`)<br>• Two-Way Data Binding (`[(ngModel)]` & Signal `model()`) | [angular.dev/guide/templates/binding](https://angular.dev/guide/templates/binding)<br>[angular.dev/guide/templates/two-way-binding](https://angular.dev/guide/templates/two-way-binding) |
| [**Module 03**](./03_directives_and_component_communication.md) | [03. Directives, Component Communication & Content Projection](./03_directives_and_component_communication.md) | • Directives Overview (Component, Structural, Attribute)<br>• Structural Directives (`*ngIf`, `*ngFor` + `trackBy`, `*ngSwitch`) & Modern Control Flow (`@if`, `@for`, `@switch`)<br>• Attribute Directives (`[ngClass]`, `[ngStyle]`)<br>• Template Reference Variables (`#var`)<br>• Parent-Child Communication (`@Input`, `@Output`, `EventEmitter` & Signals)<br>• `@ViewChild` vs. Two-Way Binding<br>• Content Projection (`<ng-content>`) | [angular.dev/guide/directives](https://angular.dev/guide/directives)<br>[angular.dev/guide/components/inputs](https://angular.dev/guide/components/inputs)<br>[angular.dev/guide/components/content-projection](https://angular.dev/guide/components/content-projection) |

---

## 🛠️ Prerequisites & Local Setup

### 1. System Requirements
- **Node.js**: `v18.13.0` or higher (LTS recommended)
- **npm**: `v9.0.0` or higher
- **Angular CLI**: Latest version

### 2. Quick Start

```bash
# 1. Install Angular CLI globally
npm install -g @angular/cli

# 2. Create a new Angular application (Standalone by default)
ng new my-angular-app

# 3. Navigate into project directory
cd my-angular-app

# 4. Start local development server (accessible at http://localhost:4200)
ng serve -o
```

---

## 🌐 Official Documentation & Resources

- 📖 **Official Angular Documentation:** [angular.dev](https://angular.dev)
- 🚀 **Angular CLI Reference:** [angular.dev/tools/cli](https://angular.dev/tools/cli)
- 💡 **Interactive Tutorials:** [angular.dev/tutorials](https://angular.dev/tutorials)