# playwrightnewtest

playwright-framework-excel/
├── .github/
│   └── workflows/
│       └── playwright.yml             # GitHub Actions CI workflow
│
├── config/
│   ├── env/
│   │   ├── dev.env                    # Dev environment variables
│   │   ├── stage.env                  # Staging environment variables
│   │   └── prod.env                   # Production environment variables
│   └── testConfig.ts                 # Loads env based on TEST_ENV
│
├── data/
│   └── utils.ts                      # Excel reader + data resolver
│
├── pages/
│   └── LoginPage.ts                 # Page Object Model (POM) for login
│
├── reports/
│   └── html-report/                 # HTML test rep
