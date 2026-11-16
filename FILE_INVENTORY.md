# File inventory - AWS DevOps GitHub repository

This inventory lists the files included in this ZIP. Every path is relative to the extracted repository root.

**Read first:** `README.md`, followed by `docs/RUN_ALL_SCRIPTS.md`.

The ZIP contains **source code**, not a prebuilt container image or deployed AWS environment.

## Python scripts (5)

- `scripts/check_endpoint.py`
- `scripts/docker_runner.py`
- `scripts/export_validation_pdf.py`
- `scripts/generate_validation_report.py`
- `scripts/preflight.py`

## Python app and tests (5)

- `app/app.py`
- `tests/test_app.py`
- `tests/test_check_endpoint.py`
- `tests/test_docker_runner.py`
- `tests/test_replication_script.py`

## Terraform source and environment examples (16)

- `terraform/environments/prod-primary/backend.hcl.example`
- `terraform/environments/prod-primary/main.tf`
- `terraform/environments/prod-primary/terraform.tfvars.example`
- `terraform/environments/prod-primary/versions.tf`
- `terraform/environments/prod-secondary/backend.hcl.example`
- `terraform/environments/prod-secondary/main.tf`
- `terraform/environments/prod-secondary/terraform.tfvars.example`
- `terraform/environments/prod-secondary/versions.tf`
- `terraform/environments/stage/backend.hcl.example`
- `terraform/environments/stage/main.tf`
- `terraform/environments/stage/terraform.tfvars.example`
- `terraform/environments/stage/versions.tf`
- `terraform/modules/regional_app/main.tf`
- `terraform/modules/regional_app/outputs.tf`
- `terraform/modules/regional_app/variables.tf`
- `terraform/modules/regional_app/versions.tf`

## Docker and CI (6)

- `.github/workflows/ci.yml`
- `app/.dockerignore`
- `app/Dockerfile`
- `buildspec.smoke.yml`
- `buildspec.yml`
- `compose.yaml`

## Shell and PowerShell helpers (10)

- `scripts/build_push_ecr.sh`
- `scripts/check_deployment.sh`
- `scripts/check_local.sh`
- `scripts/create_ecr_repositories.sh`
- `scripts/create_state_bucket.sh`
- `scripts/mirror_source.sh`
- `scripts/run_docker.ps1`
- `scripts/terraform_check.sh`
- `scripts/verify_replication.sh`
- `scripts/write_secondary_imagedefinitions.sh`

## Reports and project PDF (8)

- `docs/source/Logicworks_AWS_DevOps_Final_Certification_Project.pdf`
- `reports/DEPLOYMENT_TEST_REPORT_TEMPLATE.md`
- `reports/LOCAL_VERIFICATION_REPORT.md`
- `reports/LOCAL_VERIFICATION_REPORT.pdf`
- `reports/PROJECT_IMPLEMENTATION_STATUS.md`
- `reports/README.md`
- `reports/generated/validation_report.json`
- `reports/generated/validation_report.md`

## Documentation and setup (11)

- `README.md`
- `app/requirements.txt`
- `docs/ARCHITECTURE.md`
- `docs/DEPLOYMENT_GUIDE.md`
- `docs/GITHUB_UPLOAD.md`
- `docs/REQUIREMENT_TRACEABILITY.md`
- `docs/RUN_ALL_SCRIPTS.md`
- `docs/SECURITY_AND_COST.md`
- `docs/TEST_AND_EVIDENCE.md`
- `docs/TROUBLESHOOTING.md`
- `requirements-dev.txt`

