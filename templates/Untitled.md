<%*
const tagToAppend = "##Todo_question";
const activeFile = tp.file.title;
const targetFile = "Todo Collector";

const referenceLine = `![${activeFile}${tagToAppend}]`;

await tp.file.append_to(targetFile, referenceLine + "\n");
%>
