let box= document.querySelector("#box");
let notesContainer= document.querySelector(".notes-container");
let current =box;
box.addEventListener("click",()=>{
    let p=document.createElement("p");
    p.setAttribute("class","input-box");
    p.setAttribute("contenteditable","true");

    let delete_img =document.createElement("img");
    delete_img.setAttribute("class","deleteimg");
    delete_img.src= "images/delete.png";
    p.appendChild(delete_img);
    notesContainer.appendChild(p);
    current.after(p);

    delete_img.addEventListener("click",()=>{
        p.remove();
    })
});
