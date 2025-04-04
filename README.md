# UQParkSmart
A smart parking app that provides real-time parking availability, predictive alerts, and smart recommendations for University of Queensland students and staff.

import matplotlib.pyplot as plt
import networkx as nx

# Create a graph to represent the tree structure
G = nx.DiGraph()

# Add nodes (features and details)
G.add_node("ParkPulse/UQ Park Smart")
G.add_node("Core Features")
G.add_node("1. Live Car Park Availability")
G.add_node("2. Predictive Notifications")
G.add_node("3. Smart Recommendations")
G.add_node("4. Weather-Based Alerts")
G.add_node("5. Peak Hour Forecasting")
G.add_node("6. User Reports / Crowd-Sourced Input")
G.add_node("7. Integration with Student Schedules")
G.add_node("Feasibility & Tech Stack Thoughts")
G.add_node("Target Market & Potential Expansion")
G.add_node("Business Model Ideas")
G.add_node("Freemium Model")
G.add_node("B2B Licensing Model")
G.add_node("Data Licensing / Insights")

# Add edges (connections between features and related details)
G.add_edges_from([
    ("ParkPulse/UQ Park Smart", "Core Features"),
    ("Core Features", "1. Live Car Park Availability"),
    ("Core Features", "2. Predictive Notifications"),
    ("Core Features", "3. Smart Recommendations"),
    ("Core Features", "4. Weather-Based Alerts"),
    ("Core Features", "5. Peak Hour Forecasting"),
    ("Core Features", "6. User Reports / Crowd-Sourced Input"),
    ("Core Features", "7. Integration with Student Schedules"),
    ("ParkPulse/UQ Park Smart", "Feasibility & Tech Stack Thoughts"),
    ("ParkPulse/UQ Park Smart", "Target Market & Potential Expansion"),
    ("ParkPulse/UQ Park Smart", "Business Model Ideas"),
    ("Business Model Ideas", "Freemium Model"),
    ("Business Model Ideas", "B2B Licensing Model"),
    ("Business Model Ideas", "Data Licensing / Insights"),
])

# Position the nodes for a clean layout
pos = nx.spring_layout(G)

# Draw the graph
plt.figure(figsize=(10, 10))
nx.draw(G, pos, with_labels=True, node_size=4000, node_color="skyblue", font_size=10, font_weight="bold", edge_color="gray")
plt.title("ParkPulse/UQ Park Smart App Tree of Features and Future Plans", size=15)
plt.show()

