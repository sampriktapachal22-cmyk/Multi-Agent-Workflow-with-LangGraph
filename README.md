Why Use LangGraph for This?
Separation of Concerns: Instead of forcing one prompt to handle tool execution and heavy stylistic writing simultaneously, each agent focuses on a single specialized objective (gathering vs. writing).

Explicit State Management (TypedDict): The state explicitly tracks what data has been passed between nodes, making debugging straightforward.

Scalability: You can easily insert additional nodes into the graph later—such as a fact_checker node between the researcher and writer, or a conditional router that decides whether more research is needed before writing.
