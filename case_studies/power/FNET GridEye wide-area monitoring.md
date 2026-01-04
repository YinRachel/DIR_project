# Case Study: FNET GridEye Wide-Area Frequency Monitoring
https://en.wikipedia.org/wiki/FNET


## Context
The Frequency Monitoring Network (FNET), later known as GridEye, is a wide-area monitoring system developed to observe the dynamic behavior of large-scale electric power systems in real time. It is deployed across the United States and uses geographically distributed frequency disturbance recorders (FDRs), which are low-cost, time-synchronised measurement devices connected via the internet.

The system was originally developed in an academic–industry collaboration context and is now used to support grid situational awareness, research, and operator understanding of large-scale power system dynamics.

## Disruption or Risk Context
Large interconnected power systems are vulnerable to:
- Cascading failures triggered by local disturbances
- Frequency instability following generator outages or line trips
- Limited situational awareness due to sparse or delayed measurements

Historically, operators relied on SCADA systems with relatively low temporal resolution, which constrained their ability to detect and interpret fast dynamic events that can escalate into widespread blackouts.

## Digitalisation Approach
FNET/GridEye applies digitalisation through:
- Distributed frequency disturbance recorders (FDRs) installed across the grid
- Time-synchronised measurements enabled by GPS
- Internet-based data transmission to central servers
- Real-time data analytics and visualisation dashboards

Unlike traditional PMU deployments focused on substations, FNET leverages a dense, low-cost sensor network to provide wide-area frequency measurements, enabling system-level observation rather than asset-level control.

## Resilience Outcomes
The deployment of FNET/GridEye has contributed to:
- Improved real-time situational awareness of grid frequency behavior
- Earlier detection of disturbances and abnormal system dynamics
- Better understanding of inter-area oscillations and system inertia
- Enhanced post-event analysis to support learning and adaptation

These capabilities support the absorptive and adaptive capacities of the power system by enabling faster operator response and informed decision-making during disturbances.

## Limitations and Trade-offs
Despite its benefits, the FNET/GridEye approach has limitations:
- Reliance on telecommunications and internet connectivity
- Limited direct control capability (monitoring-focused rather than actuation)
- Data interpretation still requires expert human oversight
- Cybersecurity considerations due to distributed and internet-connected devices

Additionally, while low-cost sensors enable wide coverage, they may not provide the same measurement precision as high-end PMUs.

## Key Lessons for Infrastructure Resilience
- Wide-area situational awareness is critical for managing systemic risk
- Low-cost, distributed digital sensing can significantly enhance resilience
- Monitoring infrastructure can deliver resilience benefits even without direct control
- Digital systems should complement, not replace, human decision-making
- Learning from disturbances is a core component of long-term resilience

## Links to Related Sections

