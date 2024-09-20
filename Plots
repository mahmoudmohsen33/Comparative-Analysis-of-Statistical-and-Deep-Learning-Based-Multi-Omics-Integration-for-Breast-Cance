# ------------------------------
# Load necessary libraries
# ------------------------------
library(readxl)
library(circlize)
library(fmsb)
library(UpSetR)
# ------------------------------
# chord_diagram for Cancer-related Pathways
# ------------------------------
# Read Cancer-related Pathways from Excel file
Cancer-related Pathways <- read_excel("top-Cancer-related Pathways2.xlsx")
# Check column names
colnames(Cancer-related Pathways)
# Prepare links Cancer-related Pathways by filtering out zero hits
links <- data.frame(
  from = rep(Cancer-related Pathways$`Cancer-related Pathways`, each = 2),
  to = rep(c("MOFA", "MoGCN"), times = nrow(Cancer-related Pathways)),
  value = c(rbind(Cancer-related Pathways$MOFA, Cancer-related Pathways$MoGCN))
)
# Filter out rows where value is zero
links <- links[links$value != 0,]
# Save plot as PNG with high resolution
png("high_quality_chord_diagram.png", width = 2000, height = 2100, res = 600)
# Ensure a new plot is created
plot.new()
# Initialize Chord diagram
circos.clear()
circos.par(gap.after = c(rep(2, length(unique(links$from))-1), 10, rep(2, length(unique(links$to))-1), 10))
# Generate the Chord diagram
chordDiagram(
  links,
  transparency = 0.5,
  annotationTrack = "grid",
  preAllocateTracks = 1
)
# Add labels to the sectors with adjusted text size
circos.track(track.index = 1, panel.fun = function(x, y) {
  sector.index = get.cell.meta.data("sector.index")
  xcenter = get.cell.meta.data("xcenter")
  circos.text(xcenter, 1.05, sector.index, facing = "reverse.clockwise", niceFacing = TRUE, cex = 0.5)
}, bg.border = NA)
# Clear the circos plot
circos.clear()
# Close the PNG device
dev.off()
# ------------------------------
# chord_diagram for Cellular Processes and Metabolism Pathways
# ------------------------------
# Read Cellular Processes and Metabolism Pathways from Excel file
Cellular Processes and Metabolism Pathways <- read_excel("Cellular Processes and Metabolism Pathways.xlsx")
# Check column names
colnames(Cellular Processes and Metabolism Pathways)
# Prepare links Cellular Processes and Metabolism Pathways by filtering out zero hits
links <- data.frame(
  from = rep(Cellular Processes and Metabolism Pathways$`Cellular Processes and Metabolism Pathways`, each = 2),
  to = rep(c("MOFA", "MoGCN"), times = nrow(Cellular Processes and Metabolism Pathways)),
  value = c(rbind(Cellular Processes and Metabolism Pathways$MOFA, Cellular Processes and Metabolism Pathways$MoGCN))
)
# Filter out rows where value is zero
links <- links[links$value != 0,]
# Save plot as PNG with high resolution
png("high_quality_chord_diagram.png", width = 2000, height = 2000, res = 300)
# Ensure a new plot is created
plot.new()
# Initialize Chord diagram
circos.clear()
circos.par(gap.after = c(rep(2, length(unique(links$from))-1), 10, rep(2, length(unique(links$to))-1), 10))
# Generate the Chord diagram
chordDiagram(
  links,
  transparency = 0.5,
  annotationTrack = "grid",
  preAllocateTracks = 1
)
# Add labels to the sectors with adjusted text size
circos.track(track.index = 1, panel.fun = function(x, y) {
  sector.index = get.cell.meta.data("sector.index")
  xcenter = get.cell.meta.data("xcenter")
  circos.text(xcenter, 1.05, sector.index, facing = "reverse.clockwise", niceFacing = TRUE, cex = 0.5)
}, bg.border = NA)
# Clear the circos plot
circos.clear()
# Close the PNG device
dev.off()
# ------------------------------
# chord_diagram for Immune System and Inflammation
# ------------------------------
# Read Immune System and Inflammation from Excel file
Immune System and Inflammation <- read_excel("Immune System and Inflammation Pathways.xlsx")
# Check column names
colnames(Immune System and Inflammation)
# Prepare links Immune System and Inflammation by filtering out zero hits
links <- data.frame(
  from = rep(Immune System and Inflammation$`Immune System and Inflammation Pathways`, each = 2),
  to = rep(c("MOFA", "MoGCN"), times = nrow(Immune System and Inflammation)),
  value = c(rbind(Immune System and Inflammation$MOFA, Immune System and Inflammation$MoGCN))
)
# Filter out rows where value is zero
links <- links[links$value != 0,]
# Save plot as PNG with high resolution
png("high_quality_chord_diagram.png", width = 2000, height = 2000, res = 600)
# Ensure a new plot is created
plot.new()
# Initialize Chord diagram
circos.clear()
circos.par(gap.after = c(rep(2, length(unique(links$from))-1), 10, rep(2, length(unique(links$to))-1), 10))
# Generate the Chord diagram
chordDiagram(
  links,
  transparency = 0.5,
  annotationTrack = "grid",
  preAllocateTracks = 1
)
# Add labels to the sectors with adjusted text size
circos.track(track.index = 1, panel.fun = function(x, y) {
  sector.index = get.cell.meta.data("sector.index")
  xcenter = get.cell.meta.data("xcenter")
  circos.text(xcenter, 1.05, sector.index, facing = "reverse.clockwise", niceFacing = TRUE, cex = 0.5)
}, bg.border = NA)
# Clear the circos plot
circos.clear()
# Close the PNG device
dev.off()
# ------------------------------
# chord_diagram for Signal Transduction Pathways
# ------------------------------
# Read Signal Transduction Pathways from Excel file
Signal Transduction Pathways <- read_excel("Signal Transduction Pathways.xlsx")
# Check column names
colnames(Signal Transduction Pathways)
# Prepare links Signal Transduction Pathways by filtering out zero hits
links <- data.frame(
  from = rep(Signal Transduction Pathways$`Signal Transduction Pathways`, each = 2),
  to = rep(c("MOFA", "MoGCN"), times = nrow(Signal Transduction Pathways)),
  value = c(rbind(Signal Transduction Pathways$MOFA, Signal Transduction Pathways$MoGCN))
)
# Filter out rows where value is zero
links <- links[links$value != 0,]
# Save plot as PNG with high resolution
png("high_quality_chord_diagram.png", width = 2000, height = 2000, res = 600)
# Ensure a new plot is created
plot.new()
# Initialize Chord diagram
circos.clear()
circos.par(gap.after = c(rep(2, length(unique(links$from))-1), 10, rep(2, length(unique(links$to))-1), 10))
# Generate the Chord diagram
chordDiagram(
  links,
  transparency = 0.5,
  annotationTrack = "grid",
  preAllocateTracks = 1
)
# Add labels to the sectors with adjusted text size
circos.track(track.index = 1, panel.fun = function(x, y) {
  sector.index = get.cell.meta.data("sector.index")
  xcenter = get.cell.meta.data("xcenter")
  circos.text(xcenter, 1.05, sector.index, facing = "reverse.clockwise", niceFacing = TRUE, cex = 0.5)
}, bg.border = NA)
# Clear the circos plot
circos.clear()
# Close the PNG device
dev.off()
# ------------------------------
# rader plot for the netwrok of MOGCN and MOFA
# ------------------------------

# Load the data
MOFA_nodes <- read.csv('MOFA_node_table.csv')
MoGCN_nodes <- read.csv('MoGCN_node_table.csv')
# Ensure both datasets have the same nodes
common_nodes <- intersect(MOFA_nodes$Id, MoGCN_nodes$Id)
MOFA_nodes <- MOFA_nodes[MOFA_nodes$Id %in% common_nodes, ]
MoGCN_nodes <- MoGCN_nodes[MoGCN_nodes$Id %in% common_nodes, ]
# Sort both dataframes by Id
MOFA_nodes <- MOFA_nodes[order(MOFA_nodes$Id), ]
MoGCN_nodes <- MoGCN_nodes[order(MoGCN_nodes$Id), ]
# Compute Euclidean distances
degree_distances <- sqrt((MOFA_nodes$Degree - MoGCN_nodes$Degree)^2)
betweenness_distances <- sqrt((MOFA_nodes$Betweenness - MoGCN_nodes$Betweenness)^2)
# Calculate average distances
average_degree_distance <- mean(degree_distances)
average_betweenness_distance <- mean(betweenness_distances)
# Log transformation to scale values
average_degree_distance_log <- log1p(average_degree_distance)
average_betweenness_distance_log <- log1p(average_betweenness_distance)
edge_distances <- c(log1p(0.3), log1p(0.2))
# Combine data into a dataframe with a dummy variable
data <- data.frame(
  Degree = c(average_degree_distance_log, edge_distances[1], 0),
  Betweenness = c(average_betweenness_distance_log, edge_distances[2], 0),
  Dummy = c(1, 1, 1) 
)
# Normalize data
max_val <- max(data)
data <- data / max_val
# Transpose the dataframe for radar chart
data <- as.data.frame(t(data))
# Add a row of maximum values for scaling
data <- rbind(rep(1, ncol(data)), rep(0, ncol(data)), data)
# Check the final dataframe structure
print(data)
# Plot radar chart
colors_border <- c(rgb(0.2, 0.5, 0.5, 0.9), rgb(0.8, 0.2, 0.5, 0.9))
colors_in <- c(rgb(0.2, 0.5, 0.5, 0.4), rgb(0.8, 0.2, 0.5, 0.4))
radarchart(data, axistype=1, 
           pcol=colors_border, pfcol=colors_in, plwd=2, plty=1,
           cglcol="grey", cglty=1, axislabcol="grey", caxislabels=seq(0, 1, 0.2), cglwd=0.8,
           vlcex=0.8)
legend(x=1, y=1, legend=c("Node Distance", "Edge Distance"), bty="n", pch=20, 
       col=colors_border, text.col="black", cex=1.2, pt.cex=3)

# ------------------------------
# Upset plot for the netwrok of MOGCN and MOFA
# ------------------------------
# Load the data
MOFA_node_table <- read.csv("MOFA_node_table.csv")
MoGCN_node_table <- read.csv("MoGCN_node_table.csv")
# Create lists of node IDs for each network
MOFA_nodes <- MOFA_node_table$Id
MoGCN_nodes <- MoGCN_node_table$Id
# Combine them into a named list
node_list <- list(MOFA = MOFA_nodes, MoGCN = MoGCN_nodes)
upset(fromList(node_list), 
      order.by = "freq", 
      main.bar.color = "darkgreen", 
      sets.bar.color = "darkgray", 
      sets = c("MOFA", "MoGCN"), 
      keep.order = TRUE, 
      point.size = 3, 
      line.size = 1)
# ------------------------------
# Venn diagram for the netwrok of MOGCN and MOFA
# ------------------------------
# Load the data
MoGCN_enrichment <- read.csv("MoGCN_omicsnet_enrichment_1.csv")
MOFA_enrichment <- read.csv("MOFA_omicsnet_enrichment_1.csv")
# Filter significant pathways
MoGCN_significant <- MoGCN_enrichment$Pathway[MoGCN_enrichment$FDR < 0.05]
MOFA_significant <- MOFA_enrichment$Pathway[MOFA_enrichment$FDR < 0.05]
# Create a Venn diagram
venn.plot <- venn.diagram(
  x = list(
    MoGCN = MoGCN_significant,
    MOFA = MOFA_significant
  ),
  category.names = c("MoGCN", "MOFA"),
  filename = NULL, # NULL to plot in R console
  fill = c("red", "blue"),
  alpha = 0.5,
  cex = 1.5,
  fontface = "bold",
  fontfamily = "sans"
)
# Plot the Venn diagram
grid.newpage()
grid.draw(venn.plot)
