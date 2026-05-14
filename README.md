# Incremental Modernization of a Legacy University Timetable Web Application

**Author:** Kristína Király Rybárová

**Supervisor:** Mgr. Marek Šuppa

## Annotation

Candle is a production academic web application for timetable browsing and personal schedule construction operated by a student team at FMFI UK, currently implemented as a legacy PHP/Symfony 1.x system with multiple integration points (e.g., authentication and calendar export). This thesis aims to perform an engineering case study of porting Candle to a modern stack in 2025 while preserving externally observable behavior, using an incremental displacement strategy (Strangler Fig) rather than a big-bang rewrite. The work will emphasize regression-safety through a migration-oriented test strategy (characterization/approval tests plus a balanced automated test portfolio), guided by contemporary testing practice and evaluated not only via coverage but also via mutation testing to estimate fault-detection capability as the system is progressively replatformed. The study design will follow established case study methodology to triangulate technical artifacts and outcomes (repository mining, test metrics, pipeline telemetry, and developer feedback) into transferable guidance for modernizing small-team academic production systems.
