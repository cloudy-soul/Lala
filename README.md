# Lala

src/
├── app/
│   ├── core/               # Global services, guards, interceptors
│   │   ├── services/
│   │   │   ├── auth.service.ts
│   │   │   ├── user.service.ts
│   │   │   └── formation.service.ts
│   │   ├── interceptors/
│   │   │   └── auth.interceptor.ts
│   │   └── guards/
│   │       └── auth.guard.ts
│
│   ├── shared/             # Reusable components, pipes, directives, interfaces
│   │   ├── components/
│   │   │   └── navbar.component.ts
│   │   ├── models/
│   │   │   ├── user.model.ts
│   │   │   └── formation.model.ts
│   │   └── pipes/
│   │       └── date-format.pipe.ts
│
│   ├── auth/               # Authentication module
│   │   ├── login/
│   │   │   └── login.component.ts
│   │   ├── register/       # Optional
│   │   │   └── register.component.ts
│   │   └── auth-routing.module.ts
│
│   ├── admin/              # Admin-specific module
│   │   ├── dashboard/
│   │   │   └── admin-dashboard.component.ts
│   │   ├── users/
│   │   │   └── user-list.component.ts
│   │   └── admin-routing.module.ts
│
│   ├── candidat/           # Candidat-specific module
│   │   ├── dashboard/
│   │   │   └── candidat-dashboard.component.ts
│   │   ├── formations/
│   │   │   ├── formation-list.component.ts
│   │   │   └── formation-detail.component.ts
│   │   └── candidat-routing.module.ts
│
│   ├── app-routing.module.ts
│   └── app.component.ts
│
├── assets/
│   └── styles/
│       └── main.scss
├── environments/
│   ├── environment.ts
│   └── environment.prod.ts
└── index.html
