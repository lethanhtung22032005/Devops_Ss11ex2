# DevOps_Ss11ex2

Bài 2: Biên dịch đóng gói tệp ứng dụng .jar với Gradle và lưu trữ Artifacts.

Workflow CI (`./gradlew bootJar`) đóng gói ứng dụng Spring Boot và lưu trữ thành phẩm `build/libs/*.jar` lên GitHub Actions dưới tên artifact `app-jar`.

## Kết quả

- Workflow: `.github/workflows/ci.yml`
- Artifact: `app-jar` (`build/libs/*.jar`)
- Ảnh minh chứng: `screenshots/actions-summary-app-jar.png`
