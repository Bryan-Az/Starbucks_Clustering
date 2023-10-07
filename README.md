# Starbucks_Clustering
Using fabricated 'Starbucks' data to test run Agglomerative Clustering methods

# Findings

## Single-Link

### Time-Slots Generated

This gives the following in order of importance:

1. Cluster 1 (Morning time-slot): 6am-9am (3 hours)
2. Cluster 2 (Early Evening): 1pm-4pm (3 hours)

Sidenote: Cluster three only has one data point, so I would advise the starbucks manager to ignore this cluster. However, I would still mention the data being dropped was:

Cluster 3 (High Noon):12pm-1pm (1 hour)

## Complete-Link

### Time Slots Generated

This gives the following in order of importance:

1. Cluster 3 (Morning time-slot): 8am-12pm (4 hours)
2. Cluster 2 (Early Morning): 6am-8am (2 hours)
3. Cluster 1 (Early Evening):1pm-4pm (3 hours)

Sidenote: Since Cluster 2/3 have similar sizes, I would advise the manager to prioritize these two time slots equally. Also, cluster 4 was dropped due to insufficient size.

## Average-Link

### Time Slots Generated

This gives the following in order of importance:

1. Cluster 3 (Morning time-slot): 6am-10am (4 hours)
2. Cluster 1 (Early Evening time-slot): 1pm-4pm (3 hours)

Sidenote: Clusters 2/4 were dropped due to insufficient size.
