```bash
my-cypress-project/
├── cypress/
│ ├── e2e/
│ │ ├── example.feature
│ │ └── steps/
│ │ └── example.js
│ ├── support/
│ │ └── steps/
│ │ └── another-example.js
├── .cypress-cucumber-preprocessorrc
├── cypress.json
├── package.json
└── cypress.config.js
```

# Cấu hình Cypress Cucumber Preprocessor

Dự án này sử dụng [@badeball/cypress-cucumber-preprocessor](https://github.com/badeball/cypress-cucumber-preprocessor) để viết các kịch bản kiểm thử (tests) bằng ngôn ngữ Gherkin. Tệp `.cypress-cucumber-preprocessorrc` được sử dụng để cấu hình cách preprocessor xử lý các tệp `.feature` và các bước kiểm thử (step definitions).

## Tệp `.cypress-cucumber-preprocessorrc`
