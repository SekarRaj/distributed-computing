# Thundering Herd Problem

Too many request coming at once, which causes stampede in the system, causing lag, dropout and disconnection.

## Solution
Network of edge caches distributes around the globe. Using proxy in the edge to check if the requested content is already in the edge, if present, returns from the edge. If not the proxy requests the origin cache for the content, which in turn directs to the origin server if not found in the origin cache.