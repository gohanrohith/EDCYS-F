EDCYS/
├── .idx/
│   ├── airules.md
│   ├── dev.nix
│   └── integrations.json
├── Assets/
│   ├── cbse-branding/
│   │   ├── brand-guidelines.md
│   │   └── color-palette.md
│   ├── icons/
│   │   ├── icon-design-guidelines.md
│   │   └── safal-iconography.md
│   ├── images/
│   │   └── placeholder-images.md
│   ├── logos/
│   │   └── logo-usage-guidelines.md
│   ├── mobile-assets/
│   │   ├── responsive-images.md
│   │   └── touch-targets.md
│   └── safal-materials/
│       ├── cognitive-level-assets.md
│       └── competency-icons.md
├── BackEnd/
│   ├── config/
│   │   ├── constants.js
│   │   ├── jwt.js
│   │   ├── mongodb.js
│   │   ├── postgresql.js
│   │   └── redis.js
│   ├── controllers/
│   │   ├── ActivityControllers/
│   │   │   └── activityTrackingController.js
│   │   ├── AssignmentControllers/
│   │   │   ├── assignmentController.js
│   │   │   └── submissionController.js
│   │   ├── QuestionControllers/
│   │   │   ├── questionAnalysingController.js
│   │   │   ├── questionApplyingController.js
│   │   │   ├── questionEvaluatingController.js
│   │   │   ├── questionRememberingController.js
│   │   │   └── questionUnderstandingController.js
│   │   ├── UserControllers/
│   │   │   ├── authController.js
│   │   │   ├── individualStudentController.js
│   │   │   ├── schoolAdminController.js
│   │   │   ├── schoolStudentController.js
│   │   │   ├── schoolTeacherController.js
│   │   │   └── superAdminController.js
│   │   └── WebsiteControllers/
│   │       ├── homeController.js
│   │       ├── paymentController.js
│   │       ├── productController.js
│   │       └── registrationController.js
│   ├── middleware/
│   │   ├── auth.js
│   │   ├── roleAuth.js
│   │   ├── schoolAuth.js
│   │   └── validation.js
│   ├── models/
│   │   ├── Activity/
│   │   │   ├── AssessmentActivity.js
│   │   │   └── StudentActivity.js
│   │   ├── Assignments/
│   │   │   ├── Assignment.js
│   │   │   └── StudentAssignment.js
│   │   ├── Questions/
│   │   │   ├── Question_Analysing.js
│   │   │   ├── Question_Applying.js
│   │   │   ├── Question_Evaluating.js
│   │   │   ├── Question_Remembering.js
│   │   │   └── Question_Understanding.js
│   │   ├── SAFAL/
│   │   │   ├── LearningGaps.js
│   │   │   └── SAFALReport.js
│   │   ├── Users/
│   │   │   ├── IndividualStudent.js
│   │   │   ├── SchoolAdmin.js
│   │   │   ├── SchoolStudent.js
│   │   │   ├── SchoolTeacher.js
│   │   │   └── SuperAdmin.js
│   │   └── Website/
│   │       ├── Payment.js
│   │       ├── Product.js
│   │       └── Registration.js
│   ├── routes/
│   │   ├── Activity/
│   │   │   └── activityRoutes.js
│   │   ├── Assignments/
│   │   │   └── assignmentRoutes.js
│   │   ├── Questions/
│   │   │   ├── questionAnalysingRoutes.js
│   │   │   ├── questionApplyingRoutes.js
│   │   │   ├── questionEvaluatingRoutes.js
│   │   │   ├── questionRememberingRoutes.js
│   │   │   └── questionUnderstandingRoutes.js
│   │   ├── Users/
│   │   │   ├── authRoutes.js
│   │   │   ├── individualStudentRoutes.js
│   │   │   ├── schoolAdminRoutes.js
│   │   │   ├── schoolStudentRoutes.js
│   │   │   ├── schoolTeacherRoutes.js
│   │   │   └── superAdminRoutes.js
│   │   └── Website/
│   │       ├── homeRoutes.js
│   │       ├── paymentRoutes.js
│   │       ├── productRoutes.js
│   │       └── registrationRoutes.js
│   ├── services/
│   │   ├── activityTrackingService.js
│   │   ├── analyticsService.js
│   │   ├── assessmentService.js
│   │   ├── paymentService.js
│   │   └── safalService.js
│   └── utils/
│       ├── dbHelpers.js
│       ├── helpers.js
│       ├── safalHelpers.js
│       └── validators.js
├── Config/
│   ├── database/
│   │   ├── mongodb.conf
│   │   ├── postgresql.conf
│   │   └── redis.conf
│   ├── environments/
│   │   ├── development.env
│   │   ├── production.env
│   │   └── staging.env
│   └── services/
│       ├── load-balancer.conf
│       └── nginx.conf
├── Database/
│   ├── MongoDB/
│   │   ├── aggregations/
│   │   │   ├── class_performance.js
│   │   │   ├── competency_analysis.js
│   │   │   ├── learning_gaps.js
│   │   │   └── student_analytics.js
│   │   ├── collections/
│   │   │   ├── activity_logs.js
│   │   │   ├── assessment_results.js
│   │   │   ├── competency_progress.js
│   │   │   ├── multimedia_content.js
│   │   │   ├── question_bank.js
│   │   │   ├── questions.js
│   │   │   ├── safal_assessments.js
│   │   │   └── student_responses.js
│   │   ├── indexes/
│   │   │   ├── assessment_indexes.js
│   │   │   ├── question_indexes.js
│   │   │   ├── response_indexes.js
│   │   │   └── safal_indexes.js
│   │   ├── schemas/
│   │   │   ├── analytics_schema.js
│   │   │   ├── assessment_schema.js
│   │   │   ├── content_schema.js
│   │   │   ├── question_schema.js
│   │   │   ├── response_schema.js
│   │   │   └── safal_schema.js
│   │   └── seeds/
│   │       ├── demo_assessments.js
│   │       ├── safal_question_bank.js
│   │       └── sample_questions.js
│   ├── PostgreSQL/
│   │   ├── functions/
│   │   │   ├── assignment_functions.sql
│   │   │   ├── reporting_functions.sql
│   │   │   ├── safal_analytics_functions.sql
│   │   │   └── user_management_functions.sql
│   │   ├── migrations/
│   │   │   ├── 001_create_users_table.sql
│   │   │   ├── 002_create_schools_table.sql
│   │   │   ├── 003_create_classes_table.sql
│   │   │   ├── 004_create_subjects_table.sql
│   │   │   ├── 005_create_assignments_table.sql
│   │   │   ├── 006_create_safal_tables.sql
│   │   │   └── 007_create_indexes.sql
│   │   ├── schemas/
│   │   │   ├── assignments.sql
│   │   │   ├── audit_logs.sql
│   │   │   ├── chapters.sql
│   │   │   ├── classes.sql
│   │   │   ├── cognitive_levels.sql
│   │   │   ├── competency_mapping.sql
│   │   │   ├── learning_outcomes.sql
│   │   │   ├── permissions.sql
│   │   │   ├── safal_competencies.sql
│   │   │   ├── schools.sql
│   │   │   ├── subjects.sql
│   │   │   └── users.sql
│   │   └── seeds/
│   │       ├── admin_users.sql
│   │       ├── cbse_subjects.sql
│   │       ├── safal_competencies.sql
│   │       └── sample_schools.sql
│   └── Redis/
│       ├── cache-strategies/
│       │   ├── analytics_cache_strategy.md
│       │   ├── question_cache_strategy.md
│       │   └── user_cache_strategy.md
│       ├── config/
│       │   └── redis.conf
│       └── lua-scripts/
│           ├── analytics_aggregation.lua
│           └── rate_limiting.lua
├── Documentation/
│   ├── project/
│   │   ├── deployment/
│   │   │   ├── Mobile_App_Deployment.md
│   │   │   └── Production_Deployment.md
│   │   └── design/
│   │       ├── Database_Design.md
│   │       └── System_Architecture.md
│   ├── safal/
│   │   ├── assessment-guide/
│   │   │   ├── Assessment_Design.md
│   │   │   └── Competency_Mapping.md
│   │   ├── competencies/
│   │   │   ├── English_Competencies.md
│   │   │   └── Mathematics_Competencies.md
│   │   └── framework/
│   │       ├── CBSE_SAFAL_Overview.md
│   │       └── Competency_Framework.md
│   ├── technical/
│   │   ├── api/
│   │   │   ├── API_Overview.md
│   │   │   ├── Authentication_API.md
│   │   │   └── User_Management_API.md
│   │   └── database/
│   │       ├── Multi_Database_Architecture.md
│   │       ├── PostgreSQL_Guide.md
│   │       └── Redis_Caching_Guide.md
│   └── user-guides/
│       ├── individual-students/
│       │   └── Getting_Started.md
│       ├── school-admin/
│       │   └── Getting_Started.md
│       ├── students/
│       │   └── Getting_Started.md
│       └── teachers/
│           └── Getting_Started.md
├── FrontEnd/
│   ├── public/
│   │   ├── apple-touch-icon.png
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   └── manifest.json
│   └── src/
│       ├── components/
│       │   ├── Auth/
│       │   │   ├── BiometricLogin.jsx
│       │   │   └── MobileLoginForm.jsx
│       │   └── Common/
│       │       ├── ErrorBoundary.jsx
│       │       └── Loading.jsx
│       ├── context/
│       │   ├── AuthContext.js
│       │   └── SAFALContext.js
│       ├── hooks/
│       │   ├── useAuth.js
│       │   └── useResponsive.js
│       ├── pages/
│       │   ├── Auth/
│       │   │   └── MobileLogin.jsx
│       │   └── Dashboard/
│       │       └── ResponsiveSuperAdminDashboard.jsx
│       ├── services/
│       │   ├── authService.js
│       │   └── safalService.js
│       └── styles/
│           ├── global.css
│           └── mobile.css
├── Scripts/
│   ├── backup/
│   │   ├── incremental-backup.sh
│   │   └── system-backup.sh
│   ├── database/
│   │   ├── mongodb-backup.sh
│   │   └── postgresql-backup.sh
│   └── deployment/
│       ├── deploy-production.sh
│       └── deploy-staging.sh
├── Security/
│   ├── api-keys/
│   │   └── key-management-guide.md
│   └── encryption/
│       └── data-encryption-guide.md
└── Testing/
    ├── e2e-tests/
    │   └── user-workflows.spec.js
    └── unit-tests/
        ├── backend-services.spec.js
        └── frontend-components.spec.js
