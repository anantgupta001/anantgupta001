```java
package com.anantgupta;

/**
 * System Engineer @ Tata Consultancy Services
 * B.Tech Computer Science, VIT AP (2022–2026)
 * Jaipur, Rajasthan, India
 */
public class AnantGupta {

    private static final String EMAIL    = "contactguptaanant@gmail.com";
    private static final String GITHUB   = "github.com/anantgupta001";
    private static final String LINKEDIN = "linkedin.com/in/anantgupta7628";
    private static final String LEETCODE = "leetcode.com/anantgupta001";

    private final List<String> languages = List.of("Java", "SQL");

    private final List<String> frameworks = List.of(
        "Spring Boot", "Node.js", "Express", "Angular",
        "React", "Next.js", "Flutter"
    );

    private final List<String> databases = List.of(
        "PostgreSQL", "MySQL", "MongoDB", "Redis"
    );

    private final List<String> technologies = List.of(
        "Kafka", "GCP", "AWS", "Firebase",
        "Git", "JUnit", "Mockito", "SonarQube"
    );

    /**
     * Software Engineer @ TCS
     * System Engineer | C1 Band
     */
    public void currentRole() {
        // Currently working at Tata Consultancy Services.
    }

    /**
     * SDE Intern @ Growspace | Jan 2026 – Jul 2026
     * Clients: Google Pay, Wipro
     */
    public void previousRole() {
        buildSessionManagement("Spring Boot", "Redis"); // 10K+ accounts
        implementOrganizationRBAC(4000, 100, 70); // orgs, roles, permissions
        automateSIMLifecycle(20_000_000L); // configurable rules
        manageSIMTags(100_000); // bulk operations
        generateAsyncReports(100_000); // XLSX, GCS
    }

    public static void main(String[] args) {
        System.out.println("Building software. Learning. Contributing.");
    }
}
```

┌─ open-source.log ─────────────────────────────────────────────────┐

```diff
$ git log --oneline --stat --author="anantgupta001"

dbeaver/dbeaver  (Java, SWT, Eclipse RCP)

+ 6 MERGED PRs
  SQL Editor, UI rendering and desktop platform infrastructure

+ Theme synchronization
  Fixed theme inconsistencies across compiler logs, editor
  panels and result grids after runtime theme changes.

+ SQL Editor connection synchronization
  Synchronized editor tabs, toolbars, connection indicators
  and result tabs with active database connections.

+ Windows taskbar fix
  Refactored platform initialization to prevent duplicate
  taskbar icons while preserving cross-platform behavior.
```

└─────────────────────────────────────────────────────────────────┘

┌─ projects.json ─────────────────────────────────────────────────┐

```json
{
  "projects": [
    {
      "name": "VITor — Faculty Rating Platform",
      "stack": ["Next.js", "Firebase", "Tailwind CSS"],
      "live": "vitor-facultyranker.vercel.app",
      "description": "Anonymous faculty review platform across VIT campuses, with 1,500+ faculty profiles and 500+ reviews.",
      "highlights": [
        "Authenticated review APIs",
        "Campus-based authorization",
        "Rate limiting",
        "Paginated data access"
      ]
    },
    {
      "name": "CraVIT — Food Ordering Platform",
      "stack": ["Flutter", "Firebase", "Razorpay"],
      "repo": "github.com/anantgupta001/cravit",
      "description": "Cross-platform food ordering app built as a modular monorepo for students and vendors.",
      "highlights": [
        "Google Sign-In",
        "Razorpay payments",
        "Real-time order notifications with FCM"
      ]
    }
  ]
}
```

└─────────────────────────────────────────────────────────────────┘

┌─ ~/anantgupta — zsh ────────────────────────────────────────────┐

```bash
$ whoami --education

  Vellore Institute of Technology
  B.Tech, Computer Science | 2022 – 2026
  CGPA: 8.39

$ whoami --stats

  LeetCode      900+ problems solved · 1600+ rating
  CodeVita       AIR 320

$ whoami --achievements

  Intern of the Month — Growspace
  Smart India Hackathon — Finalist

$ contact --me

  Email      contactguptaanant@gmail.com
  LinkedIn   linkedin.com/in/anantgupta7628
  GitHub     github.com/anantgupta001
  LeetCode   leetcode.com/anantgupta001

$ _
```

└────────────────────────────────────────────────────────────────┘
