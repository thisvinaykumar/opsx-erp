# OpsX Features

OpsX — the Edge-Computing Workforce OS & Multi-Tenant Enterprise ERP by **Opsx Apex Private Limited**.
Back to [README](../README.md) · Website: [opsx.in](https://opsx.in/)

## 1. Geofenced Attendance
- Site geofences defined as a radius or polygon per branch / site.
- Punches captured with timestamp, GPS coordinates, accuracy and device identity.
- Out-of-fence punches are rejected or flagged for supervisor review, depending on policy.
- Shift-aware: late-in, early-out and missed-punch detection.

## 2. Dynamic Role-Based Access Control (RBAC)
- Roles and permissions are scoped per tenant and editable at runtime.
- Fine-grained permissions at module, action and data-scope level (own / team / branch / tenant).
- Every privileged action is audit-logged.

## 3. Live Tracking
- Real-time location of on-duty staff on a map.
- Movement history and timeline playback for supervisors.
- Tracking bound to duty hours to respect employee privacy.

## 4. Route Planning
- Multi-stop routes and beat plans assigned to field staff.
- Planned vs. actual visit comparison and visit-level check-ins.

## 5. Advanced Payroll Engine
- Rule-driven salary components: earnings, allowances, overtime, deductions.
- Computed directly from attendance and shift data — no manual re-entry.
- Configurable pay cycles per tenant and payslip generation.

## 6. SQLCipher-Encrypted Android Kiosk Tablets
- Shared on-site tablets for attendance at gates, factories and offices.
- Local database encrypted at rest with SQLCipher (AES-256).
- Offline-first: punches are stored securely on-device and synced when online.
- Locked-down kiosk mode so the device runs only OpsX.

## 7. Multi-Tenant ERP Core
- Many organisations on one platform with strict tenant data isolation.
- Branch, site and department hierarchies per tenant.
