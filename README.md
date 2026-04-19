<h1 align="center">Hi 👋, I'm Sujeet Jaiswara</h1>
<h3 align="center">Senior Angular Developer | Scalable Frontend Architect</h3>

<p align="center">
  🚀 Building high-performance Angular apps using Signals, Standalone APIs & modern architecture
</p>

---

## 👨‍💻 About Me

* 🧑‍💻 Angular-focused developer with strong frontend architecture experience

* 🌍 Based in India

* 🔗 Portfolio: https://sujeetjaiswara.vercel.app

* 📫 Email: [sujeetjaiswara2012@gmail.com](mailto:sujeetjaiswara2012@gmail.com)

* ⚡ Core expertise:

  * Angular 17+ (Signals, Standalone Components)
  * NgRx Signal Store
  * Reactive Forms (NonNullableFormBuilder)
  * Lazy loading & feature-based architecture
  * Performance optimization & clean code practices

---

## 🧠 Angular Mindset (Production Code Style)

```ts
import { ChangeDetectionStrategy, Component, inject } from '@angular/core';
import { FeatureStore } from './data-access/feature.store';

@Component({
  standalone: true,
  selector: 'app-feature',
  template: `
    @if (data()) {
      <feature-ui [data]="data()" />
    }
  `,
  changeDetection: ChangeDetectionStrategy.OnPush
})
export class FeatureComponent {
  private readonly store = inject(FeatureStore);

  readonly data = this.store.data; // Signal-based state
}
```

✔️ Signal-driven UI
✔️ Smart/Dumb component separation
✔️ Reactive Forms
✔️ Clean architecture
✔️ No legacy patterns

---

## 🛠️ Tech Stack

### ⚡ Core

<p>
  <img src="https://skillicons.dev/icons?i=angular,ts,js" />
</p>

### 🎨 UI & Styling

<p>
  <img src="https://skillicons.dev/icons?i=html,css,tailwind,scss" />
</p>

### ⚙️ Backend & Tools

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,redis,docker" />
</p>

### 🧰 Dev Tools

<p>
  <img src="https://skillicons.dev/icons?i=vscode,git,github,postman" />
</p>

---

## 🏗️ Featured Projects

### 🔹 HRMS System (Enterprise App)

* Modular Angular architecture
* Asset & Leave Management
* Role-based access control
* NgRx Signal Store for state management

### 🔹 Cron Expression Generator

* Angular-based utility tool
* Real-time cron parsing
* Signal-driven UI updates

👉 Add your repo links here (important for recruiters)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sujeetjaiswara&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sujeetjaiswara&theme=tokyonight" />
</p>

---

## 🎯 What I Bring

* 🚀 Scalable Angular architecture
* ⚡ High-performance applications
* 🧠 Strong debugging & problem-solving
* 📦 Clean, maintainable code
* 🤝 Team collaboration

---

## 🤝 Connect With Me

<p>
  <a href="https://sujeetjaiswara.vercel.app">🌐 Portfolio</a> •
  <a href="mailto:sujeetjaiswara2012@gmail.com">📧 Email</a> •
  <a href="https://github.com/sujeetjaiswara">GitHub</a>
</p>

---

<p align="center">
  ⚡ Focused on Angular excellence, not just frontend development
</p>
