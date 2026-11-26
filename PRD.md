**Transport Shu****tt****le System**

*Product Requirements Document (PRD)*

Project Name: Campus Shuttle & Student Transportation System 

		Course: BU-COS209

# 1. Document Overview

Product Name: Transport Shuffle

- The **Transport Shuffle System** is a digital platform designed to improve how students at Babcock University access, manage, and organize campus transportation.

- The system aims to reduce long waiting times, overcrowding at bus stops, uncertainty about shuttle arrival times, and difficulties knowing which shuttle is available or heading to a particular destination.

- Instead of students waiting without information, they can use the platform to view shuttle availability, routes, estimated arrival times, and transportation updates in one place.

# 2. Problem Statement & Opportunity

## Core Problem

Getting around Babcock University campus can sometimes be stressful, especially when students have lectures to attend, are trying to get to their hostels, or need to move between different parts of campus. Students often have to wait for available shuttles without knowing how long the wait will take or whether another shuttle is coming soon.

Long Waiting Times: Students can spend a lot of time waiting for a shuttle, especially during busy periods when many students are trying to move around at once.

Overcrowding: Students may rush to board the first available shuttle because they are unsure when another one will arrive.

Poor Transport Coordination: Shuttles may be unevenly distributed, leaving some bus stops busy while others have fewer students waiting.

Lack of Information: Students often have no easy way of knowing which shuttle is available, its destination, or when it is expected to arrive.

Lecture Delays: Transportation delays can cause students to arrive late for lectures, appointments, or other activities.

## Opportunity

Transport Shuffle aims to make campus transportation easier to manage by helping students find available shuttles and organizing passengers based on where they are going. Instead of everyone waiting and hoping to find a vehicle, students can check shuttle availability, choose their destination, and get information about the next available ride. The system can also help transport operators see where students are waiting the most, making it easier to distribute shuttles where they are needed.

# 3. Goals & Success Metrics

## Primary Objectives

Reduce the amount of time students spend waiting for campus transportation.

Make it easier for students to know which shuttle is going to their destination.

Reduce overcrowding and unnecessary rushing when boarding shuttles.

Improve the coordination of shuttle drivers and campus transport routes.

Make campus transportation more predictable, especially during peak periods.

## Key Performance Indicators (KPIs)

• Average Waiting Time — Target Goal: Reduce by at least 30%; Measurement Frequency: Weekly; Strategic Rationale: Measures whether students spend less time waiting for transport.

• Student Satisfaction — Target Goal: At least 80% positive feedback; Measurement Frequency: Monthly; Strategic Rationale: Shows whether students find the system useful.

• Shuttle Utilization — Target Goal: Improve shuttle occupancy and distribution; Measurement Frequency: Weekly; Strategic Rationale: Helps reduce poorly distributed shuttles and unnecessary trips.

• Transport Request Fulfillment — Target Goal: At least 85% of requests fulfilled; Measurement Frequency: Weekly; Strategic Rationale: Measures how effectively students are connected to available shuttles.

• Late Arrival Complaints — Target Goal: Reduce transport-related lateness complaints; Measurement Frequency: Monthly; Strategic Rationale: Measures the impact of improved transport coordination.

These targets are proposed for the project and would be adjusted after testing the system with students.

# 4. Target Audience & User Personas

## Persona 1: The Student in a Hurry

Name: David (University Student)

Context: Has lectures, appointments, and other activities around campus and usually relies on shuttles to get to different locations.

Goals: Get to his destination on time without spending too much time waiting for a shuttle.

Pain Points: Gets frustrated when he waits without knowing when a shuttle will arrive, especially when he has a lecture to attend.

## Persona 2: The Shuttle Driver

Name: Mr. James (Transport Driver)

Context: Drives students around campus and is responsible for transporting passengers between designated stops.

Goals: Pick up students efficiently, know where demand is high, and avoid unnecessary trips.

Pain Points: Sometimes gets to a stop without knowing how many students are waiting or which destinations they need to go to.

## Persona 3: The Transport Administrator

Name: Mrs. Grace (Transport Coordinator)

Context: Oversees campus shuttle operations, drivers, routes, and vehicle availability.

Goals: Keep transportation running smoothly and ensure students are not left waiting too long.

Pain Points: Difficulties monitoring shuttle availability, handling complaints, and knowing which locations need more vehicles during busy periods.

# 5. User Stories & Functional Requirements

## 1: Shuttle Request & Destination Selection

User Story: As a student, I want to select my current pickup location and destination so that I can find a shuttle that is going in the direction I need.

• Student Login: Allow students to access the system using their student details or university email. Priority: P0 (Must Have)

• Destination Selection: Allow students to choose their pickup point and desired destination. Priority: P0 (Must Have)

• Shuttle Search: Display available shuttles serving the selected destination or route. Priority: P0 (Must Have)

• Request Cancellation: Allow students to cancel a transport request if their plans change. Priority: P1 (Should Have)

##  2: Shuttle Availability & Tracking

User Story: As a student, I want to see which shuttles are available and their current status so that I know whether to wait or go to a pickup point.

• Shuttle Status: Display whether a shuttle is available, on a trip, or temporarily unavailable. Priority: P0 (Must Have)

•  Route Information: Show shuttle routes, stops, and destinations. Priority: P0 (Must Have)

• Arrival Estimate: Provide an estimated arrival time at a selected stop. Priority: P1 (Should Have)

• Live Location: Show shuttle location on a map when tracking is available. Priority: P1 (Should Have)

## 3: Passenger Grouping & Transport Shuffle

User Story: As a student, I want the system to group students going to similar destinations so that shuttles can pick up passengers more efficiently.

• Passenger Grouping: Group transport requests from students going to the same or nearby destinations. Priority: P0 (Must Have)

• Queue Management: Organize student requests into a queue based on destination and request time. Priority: P0 (Must Have)

• Shuttle Assignment: Assign available shuttles to groups of students based on their destinations and capacity. Priority: P0 (Must Have)

• Capacity Indicator: Show whether a shuttle has seats available, is nearly full, or is full. Priority: P1 (Should Have)

##  4: Driver & Admin Management

User Story: As a transport administrator, I want to monitor shuttle activities and manage routes so that campus transportation is properly coordinated.

• Driver Dashboard: Allow drivers to view assigned routes, pickup locations, and destination groups. Priority: P0 (Must Have)

• Trip Status Updates: Drivers can mark a shuttle as available, boarding, on trip, or completed. Priority: P0 (Must Have)

• Route Management: Admins can add, edit, and remove shuttle routes and stops. Priority: P0 (Must Have)

• Shuttle Management: Admins can register shuttles, update availability, and assign drivers. Priority: P0 (Must Have)

• Transport Reports: Admins can view request volumes, busy stops, and shuttle activity. Priority: P1 (Should Have)

# 6. Non-Functional Requirements

## Performance & Reliability

Response Time: The system should respond to student requests within a few seconds under normal network conditions.

System Availability: The system should be available during the university's normal transportation operating hours.

Data Updates: Shuttle availability and request statuses should update quickly so students are not relying on outdated information.

Scalability: The system should be able to support more students and shuttles if it is expanded in the future.

## Security & Privacy

Account Security: Student, driver, and admin accounts should be protected from unauthorized access.

Data Protection: Students' personal details and location-related information should only be accessible where necessary.

Access Control: Drivers should only access their assigned transport duties, while admins should have access to management features.

Secure Communication: Information exchanged between users and the system should be protected.

## Connectivity

Low Data Usage: The system should not consume too much mobile data during normal use.

Network Handling: If the internet connection is poor, the app should inform the user instead of showing misleading shuttle information.

Retry Support: Failed transport requests should be easy to retry when connectivity returns.

## Accessibility & Usability

Simple Interface: Students should be able to request a shuttle without having to go through too many steps.

Mobile Friendly: The platform should work properly on smartphones since most students will access it through their phones.

Readable Design: Text, buttons, and shuttle information should be easy to understand.

# 7. User Flow & UX Considerations

## Core User Flow: Requesting a Shuttle

 [Open Transport Shuffle] → [Select Pickup Location] → [Choose Destination] → [View Available Shuttles] → [Join Shuttle Queue / Request Ride] → [Receive Shuttle Assignment] → [Board Shuttle] → [Complete Trip]

## UX & Interface Guidelines

Minimal Steps: Requesting a shuttle should be quick and should not require filling out unnecessary information.

Clear Shuttle Status: Use clear labels such as Available, Boarding, On Trip, and Full.

Easy Destination Selection: Common campus destinations should be easy to find and select.

Simple Notifications: Inform students when a shuttle has been assigned, is arriving, or when their request has changed.

Avoid Confusion: Students should be able to tell where to wait and which shuttle to board without needing to ask several people.

# 8. Out of Scope  & Future Roadmap 

## Out of Scope for (MVP)

Payment or fare collection through the app.

Transportation outside Babcock University campus.

Booking private vehicles or taxis.

Advanced AI prediction of transport demand.

Automatic route optimization across the entire campus.

Emergency transportation services.

## Future Product Roadmap 

GPS Live Tracking: Allow students to see the real-time location of shuttles on a campus map.

Smart Demand Prediction: Use previous transport request data to identify busy periods and locations.

Automated Shuttle Scheduling: Recommend how many shuttles should be assigned to different locations based on student demand.

 Feedback & Rating System: Allow students to report transport issues and rate their experience.

v2.4 – Transport Notifications: Provide updates about delays, shuttle changes, and busy pickup points.

# 9. Risks & Mitigation Strategies

• Technical — Identified Risk: Shuttle availability information may not be updated on time. Impact Level: High Mitigation Strategy: Allow drivers to update their status easily and display the last update time.

• User Adoption — Identified Risk: Students may continue using their usual way of finding shuttles instead of the system. Impact Level: High Mitigation Strategy: Keep the system simple and make it useful without requiring lengthy registration.

• Operational — Identified Risk: Drivers may not follow assigned requests or routes consistently. Impact Level: High Mitigation Strategy: Make driver instructions clear and involve transport staff during testing and rollout.

• Connectivity — Identified Risk: Poor network connection may affect requests and updates. Impact Level: Medium Mitigation Strategy: Keep basic route information accessible and provide clear feedback when requests fail.

• Accuracy — Identified Risk: Arrival times may be inaccurate due to traffic or delays. Impact Level: Medium Mitigation Strategy: Clearly label arrival times as estimates and allow drivers to update trip status.

• Capacity — Identified Risk: More students may request a shuttle than it can carry. Impact Level: Medium Mitigation Strategy: Track shuttle capacity and prevent assignments from exceeding available seats.

# Product Summary

Transport Shuffle is intended to make moving around Babcock University easier for students by helping them find available shuttles, organize transport requests, and get to their destinations with less waiting and confusion. It also gives drivers and transport administrators a better way to coordinate shuttle operations and respond to busy periods.
