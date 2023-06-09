# Running the agent
mvn -Pnative -Dagent exec:exec@java-agent
# Building the native executable
mvn -Pnative -Dagent package