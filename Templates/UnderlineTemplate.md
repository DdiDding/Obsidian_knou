<%*
let selected = tp.file.selection();

if (!selected) {
  selected = await tp.system.prompt("Enter text to underline");
}

tR = `<u>${selected}</u>`;
%>