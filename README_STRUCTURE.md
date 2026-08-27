# CTS Project - Master Structure

This is the complete CTS Inward + Outward Java/ZK project skeleton.

Architecture:
- Root package: com.iispl.cts
- Every DAO has DAO + DAOImpl.
- Every Service has Service + ServiceImpl.
- Maker/Checker are workflow areas under inward/outward.
- BOD/EOD is centralized under operations and shared by both flows.
- Notifications are centralized.
- RRF, rejection, return and send-back are separate workflow concepts.
- Outward XML generation is a dedicated module.
- ZUL files are screen skeletons to be implemented.

The Java files contain intentionally minimal skeleton code, not business logic.
