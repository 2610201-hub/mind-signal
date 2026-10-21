const questions = [
 {tag:"상황 판단", q:"친구가 최근 수행평가를 앞두고 “진짜 다 포기하고 싶다”라고 말했다. 평소에도 힘들다는 말을 자주 했지만 오늘은 웃으면서 말한다. 가장 적절한 첫 반응은?",
  a:["웃으면서 말했으니 심각하게 받아들이지 않는다.","“왜 그렇게 말해?”라고 따지기보다, 지금 어떤 마음인지 차분히 물어본다.","괜히 일을 크게 만들 수 있으니 다른 친구에게만 조심스럽게 물어본다.","일단 공부가 끝나면 괜찮아질 테니 조언부터 해준다."], c:1,
  f:"핵심은 겉으로 웃고 있는지보다 그 말과 상황 자체를 진지하게 받아들이는 것입니다. 먼저 판단하거나 해결책을 제시하기보다 현재 마음을 확인해 보세요."},
 {tag:"대화 선택", q:"친구가 “요즘 아무것도 의미가 없는 것 같아.”라고 말했다. 다음 중 가장 적절한 반응은?",
  a:["“그래도 너보다 힘든 사람 많아.”","“그렇게 생각하면 안 돼. 긍정적으로 생각해.”","“그렇게 느끼고 있구나. 요즘 특히 힘들게 느껴지는 일이 있어?”","“걱정하지 마. 내가 비밀로 해줄 테니까 아무한테도 말하지 않을게.”"], c:2,
  f:"공감하면서 구체적으로 이야기를 이어갈 수 있는 질문이 좋습니다. 비교하거나 억지로 긍정하게 만들거나, 무조건 비밀을 약속하는 것은 적절하지 않을 수 있습니다."},
 {tag:"비밀과 안전", q:"친구가 힘든 이야기를 하면서 “이건 아무한테도 말하지 마. 약속해.”라고 부탁했다. 동시에 혼자 감당하기 어려울 정도로 위험해 보인다. 가장 적절한 태도는?",
  a:["약속했으므로 어떤 상황에서도 다른 사람에게 알리지 않는다.","친구가 화낼 수 있으니 일단 모른 척하고 기다린다.","친구의 마음을 존중하되 안전이 걱정된다면 믿을 만한 어른이나 전문적인 도움을 연결한다.","친구가 비밀을 지켜달라고 했으므로 친구의 다른 친구들에게만 알린다."], c:2,
  f:"친구의 신뢰를 존중하는 것과 안전을 지키는 것은 함께 고려해야 합니다. 위험이 걱정되는 상황이라면 혼자 떠안지 말고 믿을 만한 어른이나 전문기관의 도움을 받는 것이 중요합니다."},
 {tag:"오해 찾기", q:"다음 중 친구의 어려움을 대하는 방식으로 가장 주의해야 할 행동은?",
  a:["친구가 말하는 동안 바로 해결책을 제시하기보다 먼저 듣는다.","친구의 행동 변화가 계속된다면 다시 안부를 묻는다.","친구가 스스로 말할 준비가 될 때까지 아무런 관심도 표현하지 않는다.","혼자 해결하기 어려운 문제라면 주변 어른이나 전문기관에 도움을 요청한다."], c:2,
  f:"‘말할 때까지 기다려야 한다’고 생각해 완전히 방치하는 것은 도움이 되지 않을 수 있습니다. 부담을 주지 않는 선에서 안부를 묻고, 필요한 경우 도움을 연결하는 것이 중요합니다."},
 {tag:"우선순위", q:"친구가 며칠째 결석하고 연락도 거의 받지 않는다. 다른 친구는 “원래 잠수 잘 타잖아”라고 한다. 이때 가장 적절한 판단은?",
  a:["평소에도 그런 친구라면 이번에도 신경 쓰지 않는다.","확실한 증거가 없으니 아무 행동도 하지 않는다.","평소와 다른 변화인지 살펴보고, 걱정된다면 믿을 만한 어른에게 상황을 알린다.","친구의 사생활이므로 온라인에 공개적으로 안부를 묻는다."], c:2,
  f:"평소 모습과 다른 지속적인 변화가 있다면 단정하지 말고 안전을 확인하는 것이 중요합니다. 공개적으로 퍼뜨리기보다 신뢰할 수 있는 어른에게 상황을 전달하는 편이 적절합니다."},
 {tag:"도움 연결", q:"친구가 “상담 같은 건 필요 없어. 너한테만 말하면 돼.”라고 한다. 그런데 친구의 어려움이 계속되고 있다. 가장 적절한 말은?",
  a:["“알겠어. 그럼 앞으로 나만 믿어.”","“상담을 받아야 한다고 내가 결정할게.”","“네 이야기를 들어줄게. 다만 혼자 해결하기 어려우면 같이 도움을 찾아보자.”","“네가 상담을 거부했으니 이제 더 이상 도와줄 수 없어.”"], c:2,
  f:"친구를 대신해 결정하기보다 함께 도움을 찾겠다는 태도가 좋습니다. 친구를 혼자 책임지는 역할을 떠안지 않는 것도 중요합니다."},
 {tag:"종합 판단", q:"다음 중 가장 적절한 순서에 가까운 것은?",
  a:["문제 해결책 제시 → 감정 확인 → 전문가 연결","상황을 판단해서 결론 내리기 → 친구에게 설명하기 → 필요하면 도움 요청","변화를 알아차리기 → 차분하게 안부 묻기 → 이야기를 듣기 → 필요하면 믿을 만한 어른·전문기관과 연결","친구가 먼저 도움을 요청할 때까지 기다리기 → 그 후에만 대화하기"], c:2,
  f:"가장 중요한 흐름은 ‘알아차리기 → 대화하기 → 듣기 → 필요한 도움으로 연결하기’입니다. 친구의 문제를 혼자 해결하는 것이 목표가 아닙니다."}
];

let current=0, score=0, answered=false;
const $=id=>document.getElementById(id);
function showScreen(id){document.querySelectorAll(".screen").forEach(x=>x.classList.remove("active"));$(id).classList.add("active")}
function startGame(){current=0;score=0;showScreen("game");render()}
function render(){
 answered=false;
 const x=questions[current];
 $("progress").textContent=`${current+1} / ${questions.length}`;
 $("score").textContent=`점수 ${score}`;
 $("bar").style.width=`${((current+1)/questions.length)*100}%`;
 $("tag").textContent=x.tag;
 $("question").textContent=x.q;
 $("feedback").className="feedback";
 $("feedback").textContent="";
 $("next").style.display="none";
 $("choices").innerHTML="";
 x.a.forEach((text,i)=>{
   const b=document.createElement("button"); b.className="choice"; b.textContent=text;
   b.onclick=()=>answer(i); $("choices").appendChild(b);
 });
}
function answer(i){
 if(answered)return; answered=true;
 const x=questions[current], buttons=document.querySelectorAll(".choice");
 buttons.forEach((b,n)=>{b.disabled=true;if(n===x.c)b.classList.add("correct");else if(n===i)b.classList.add("wrong")});
 if(i===x.c)score+=Math.round(100/questions.length);
 $("feedback").textContent=(i===x.c?"✓ 정답! ":"✦ 해설: ")+x.f;
 $("feedback").classList.add("show");
 $("score").textContent=`점수 ${score}`;
 $("next").style.display="block";
}
function nextQuestion(){if(current<questions.length-1){current++;render()}else{finish()}}
function finish(){
 showScreen("result"); $("finalScore").textContent=score;
 if(score>=90){$("resultTitle").textContent="완벽해요! 상황 판단력이 뛰어나요."; $("resultText").textContent="겉으로 드러난 행동만 보고 판단하지 않고, 대화와 도움 연결의 균형을 잘 이해하고 있습니다."}
 else if(score>=70){$("resultTitle").textContent="좋아요! 중요한 원칙을 잘 알고 있어요."; $("resultText").textContent="몇몇 상황은 헷갈릴 수 있지만, 친구를 혼자 해결하려 하지 않고 적절한 도움으로 연결하는 것이 핵심입니다."}
 else{$("resultTitle").textContent="한 번 더 도전해 볼까요?"; $("resultText").textContent="이 게임의 핵심은 정답을 맞히는 것보다 ‘판단하지 않고 듣기, 혼자 떠안지 않기, 필요한 도움 연결하기’입니다."}
}
