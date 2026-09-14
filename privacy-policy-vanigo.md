<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy — Vanigo</title>
    <style>
        :root {
            --text: #1a1a1a;
            --muted: #5f6368;
            --border: #e5e7eb;
            --accent: #2563eb;
            --bg: #ffffff;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            color: var(--text);
            background: var(--bg);
            max-width: 760px;
            margin: 0 auto;
            padding: 48px 24px 96px;
            line-height: 1.65;
            font-size: 16px;
        }

        h1 {
            font-size: 28px;
            margin-bottom: 4px;
        }

        h1+p {
            color: var(--muted);
            font-size: 14px;
            margin-top: 0;
            margin-bottom: 32px;
            padding-bottom: 24px;
            border-bottom: 1px solid var(--border);
        }

        h2 {
            font-size: 19px;
            margin-top: 40px;
            margin-bottom: 12px;
            padding-bottom: 6px;
            border-bottom: 1px solid var(--border);
        }

        h3 {
            font-size: 16px;
            margin-top: 22px;
            margin-bottom: 8px;
            color: var(--text);
        }

        p {
            margin: 10px 0;
        }

        ul {
            margin: 8px 0;
            padding-left: 22px;
        }

        li {
            margin: 4px 0;
        }

        strong {
            font-weight: 600;
        }

        a {
            color: var(--accent);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .footer-note {
            margin-top: 56px;
            padding-top: 20px;
            border-top: 1px solid var(--border);
            color: var(--muted);
            font-size: 13px;
        }
    </style>
</head>

<body>
    <h1>Privacy Policy for Vanigo</h1>
    <p><strong>Last updated:</strong> September 14, 2026</p>
    <p>Vanigo ("the App", "we", "us", "our") is a school-van and student-transport management app used by Operators,
        Drivers, Parents, and Super Admins. This policy explains what information we collect, how it's used, and the
        choices you have. By using Vanigo, you agree to the practices described here.</p>
    <h2>1. Who this policy applies to</h2>
    <ul>
        <li><strong>Operators</strong> — businesses/individuals running a van/transport service who manage vehicles,
            drivers, routes, students, and fees.</li>
        <li><strong>Drivers</strong> — individuals who execute pickup/drop runs for an Operator.</li>
        <li><strong>Parents/Guardians</strong> — who link their child's account to track pickup/drop status.</li>
        <li><strong>Super Admins</strong> — Vanigo platform administrators.</li>
    </ul>
    <p>If you are a parent or guardian providing information about a child, you confirm you have the authority to do so
        and consent to this policy on the child's behalf.</p>
    <h2>2. Information we collect</h2>
    <h3>Account &amp; identity information</h3>
    <ul>
        <li>Name, email address, phone number (all roles).</li>
        <li>Government-ID type and number, submitted for identity verification (Operators and Drivers only). ID proof is
            required before an Operator or Driver account is fully activated.</li>
        <li>Vehicle registration numbers, driving license and company registration details (Operators/Drivers, where
            applicable).</li>
    </ul>
    <h3>Student information (provided by Operators/Parents)</h3>
    <ul>
        <li>Student name, school, pickup/drop addresses, parent contact number.</li>
        <li>Fee and payment records (amount, payment mode, receipts) — no card or bank account numbers are collected or
            stored by Vanigo.</li>
        <li>Attendance records (present/absent/leave, per day).</li>
        <li>Live pickup/drop status during a run (e.g. picked up, reached school, dropped home) and timestamps.</li>
    </ul>
    <h3>Location information</h3>
    <ul>
        <li>Nodal point (stop) addresses and route stop order, entered manually by Operators — Vanigo does not use
            continuous GPS tracking or a maps SDK. Location-related data is limited to addresses entered into the app
            and the live status stage of a run, not a live moving map.</li>
    </ul>
    <h3>Device &amp; technical information</h3>
    <ul>
        <li>Push-notification tokens (device-level), used to deliver in-app alerts (status updates, fee reminders,
            holidays, emergency alerts).</li>
        <li>Basic diagnostic and crash information (via Firebase Crashlytics/Analytics) to help us fix bugs and
            understand app stability. This is aggregated and not used to build advertising profiles.</li>
    </ul>
    <h3>What we do NOT collect</h3>
    <ul>
        <li>We do not collect precise, continuous GPS location in the background.</li>
        <li>We do not sell personal information to third parties.</li>
        <li>We do not use student or child data for advertising, and Vanigo does not display third-party ads.</li>
    </ul>
    <h2>3. How we use information</h2>
    <ul>
        <li>To operate the core service: managing routes, vehicles, drivers, students, fees, and attendance.</li>
        <li>To send status updates to parents when a child is picked up, reaches school, or is dropped home.</li>
        <li>To send fee reminders, holiday notices, and emergency/SOS alerts.</li>
        <li>To verify the identity of Operators and Drivers before granting them access to student data.</li>
        <li>To detect and prevent misuse, and to maintain the security of accounts and data.</li>
        <li>To fix bugs and improve reliability, using aggregated crash/diagnostic data.</li>
    </ul>
    <h2>4. Who can see what</h2>
    <p>Access to student data is scoped strictly by role:
        - <strong>Operators</strong> see the full roster, fees, routes, drivers, and vehicles they manage.
        - <strong>Drivers</strong> see only the students on the route(s) they're assigned to, and only the information
        needed to complete a run.
        - <strong>Parents</strong> see only their own linked child/children's status, fee summary, and attendance.
        - <strong>Super Admins</strong> have cross-Operator access for platform administration, driver approvals, and
        support — this access is used for administrative purposes only, not for viewing families' data without cause.
    </p>
    <p>Data belonging to one Operator's business is not accessible to another Operator.</p>
    <h2>5. Third-party services we use</h2>
    <p>Vanigo is built on Google Firebase. The following Firebase/Google services process data on our behalf, under
        their own privacy and security commitments:
        - <strong>Firebase Authentication</strong> — sign-in (Google sign-in).
        - <strong>Cloud Firestore</strong> — storage of app data (accounts, students, routes, fees, etc.).
        - <strong>Firebase Cloud Messaging (FCM)</strong> — delivery of push notifications.
        - <strong>Firebase Crashlytics &amp; Analytics</strong> — crash reporting and aggregated usage analytics.</p>
    <p>We do not share personal information with advertisers or data brokers.</p>
    <h2>6. Data retention</h2>
    <ul>
        <li>Active account and student data is retained for as long as the account is active.</li>
        <li>When an Operator removes a student, the record is held in a recovery state for a short period (a few days)
            to allow accidental-deletion recovery, after which it is permanently deleted.</li>
        <li>You may request deletion of your account and associated personal data at any time (see Section 9).</li>
    </ul>
    <h2>7. Children's data</h2>
    <p>Vanigo is designed to be used by adults (Operators, Drivers, Parents) on behalf of children; children themselves
        are not expected to directly operate the app or create their own accounts. Student records are created and
        managed by Operators and linked by verified Parent accounts. We limit the student information collected to
        what's necessary to operate a pickup/drop service (name, school, route, attendance, fee status) and do not use
        it for any purpose beyond providing the service to the family and school/operator involved.</p>
    <p>If you believe a child has provided us with personal information outside the context described above, or you are
        a parent who wants to review, correct, or delete your child's information, please contact us using the details
        in Section 9.</p>
    <h2>8. Security</h2>
    <p>We rely on Firebase's security infrastructure and apply access-control rules so that each account can only read
        or write data appropriate to its role (see Section 4). ID proof, payment records, and student data are stored in
        our Firestore database, access to which is restricted by these rules. No method of electronic storage is 100%
        secure, and we cannot guarantee absolute security, but we take reasonable steps to protect your information.</p>
    <h2>9. Your rights and choices</h2>
    <p>Depending on your role and applicable law, you may:
        - Request a copy of the personal information we hold about you or your child.
        - Request correction of inaccurate information (via your Operator, or by contacting us directly).
        - Request deletion of your account and associated data.
        - Withdraw consent for notifications by adjusting notification preferences in-app, or by disabling push
        notifications at the device level.</p>
    <p>To exercise any of these rights, contact us at the email below.</p>
    <h2>10. Changes to this policy</h2>
    <p>We may update this policy from time to time. If we make material changes, we will update the "Last updated" date
        above and, where appropriate, notify users in-app.</p>
    <h2>11. Contact us</h2>
    <p>If you have questions about this policy or how your data is handled, contact:</p>
    <p><strong>Ankit Dholakiya</strong>
        Email: dholakiyaankit@gmail.com</p>
    <div class="footer-note">Vanigo — School Van Operations App</div>
</body>

</html>
