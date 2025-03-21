<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>향 MBTI 테스트</title>
  <style>
    body {
      max-width: 600px; 
      margin: 0 auto; 
      padding: 20px; 
      font-family: sans-serif;
    }
    h1, h2 {
      text-align: center;
    }
    .question {
      margin-bottom: 15px;
    }
    .question p {
      margin: 5px 0;
      font-weight: bold;
    }
    .result {
      background: #f9f9f9; 
      padding: 15px; 
      margin-top: 20px; 
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <h1>향 MBTI(?) 테스트</h1>
  <p>아래 12문항에 답하고 "결과 보기" 버튼을 누르세요.</p>

  <!-- A축: Fresh vs Deep (3문항) -->
  <div class="question">
    <p>A-1. </p>
    <label>
      <input type="radio" name="A1" value="F" />
      (1) 활발한 모임에서 에너지를 뿜으며 즐긴다.
    </label><br>
    <label>
      <input type="radio" name="A1" value="D" />
      (2) 소수와의 깊은 대화를 더 선호한다.
    </label>
  </div>

  <div class="question">
    <p>A-2. </p>
    <label>
      <input type="radio" name="A2" value="F" />
      (1) 아침의 깨끗하고 청량한 공기를 좋아한다.
    </label><br>
    <label>
      <input type="radio" name="A2" value="D" />
      (2) 늦은 밤 잔잔하고 무거운 분위기가 좋다.
    </label>
  </div>

  <div class="question">
    <p>A-3. </p>
    <label>
      <input type="radio" name="A3" value="F" />
      (1) 신나는 음악, 운동처럼 가볍게 기분 전환한다.
    </label><br>
    <label>
      <input type="radio" name="A3" value="D" />
      (2) 독서, 사색처럼 차분하고 깊이 있는 방법을 선호한다.
    </label>
  </div>

  <!-- B축: Floral vs Woody (3문항) -->
  <div class="question">
    <p>B-1. </p>
    <label>
      <input type="radio" name="B1" value="Fl" />
      (1) 화사한 꽃무늬나 로맨틱한 분위기에 설렌다.
    </label><br>
    <label>
      <input type="radio" name="B1" value="W" />
      (2) 우드 톤이나 차분한 인테리어에 더 안정감을 느낀다.
    </label>
  </div>

  <div class="question">
    <p>B-2. </p>
    <label>
      <input type="radio" name="B2" value="Fl" />
      (1) 감정 표현이 풍부하고 다정다감한 쪽이 좋다.
    </label><br>
    <label>
      <input type="radio" name="B2" value="W" />
      (2) 담백하고 은은한 표현이 더 멋있다고 생각한다.
    </label>
  </div>

  <div class="question">
    <p>B-3. </p>
    <label>
      <input type="radio" name="B3" value="Fl" />
      (1) 꽃차나 플라워티로 기분 전환을 한다.
    </label><br>
    <label>
      <input type="radio" name="B3" value="W" />
      (2) 숲속 산책처럼 나무향이 가득한 곳에서 안정감을 찾는다.
    </label>
  </div>

  <!-- C축: Citrus vs Sweet (3문항) -->
  <div class="question">
    <p>C-1. </p>
    <label>
      <input type="radio" name="C1" value="Ci" />
      (1) 상큼하게 톡 쏘는 느낌을 선호한다.
    </label><br>
    <label>
      <input type="radio" name="C1" value="Sw" />
      (2) 달콤하고 포근한 느낌이 더 좋다.
    </label>
  </div>

  <div class="question">
    <p>C-2. </p>
    <label>
      <input type="radio" name="C2" value="Ci" />
      (1) 에너지가 떨어질 때 상큼한 주스나 탄산수로 리프레시한다.
    </label><br>
    <label>
      <input type="radio" name="C2" value="Sw" />
      (2) 초콜릿, 디저트처럼 달달한 간식으로 위안받는다.
    </label>
  </div>

  <div class="question">
    <p>C-3. </p>
    <label>
      <input type="radio" name="C3" value="Ci" />
      (1) 즉각적인 활력을 원할 때 가벼운 농담이나 빠른 액션을 취한다.
    </label><br>
    <label>
      <input type="radio" name="C3" value="Sw" />
      (2) 잔잔한 위로와 따뜻한 분위기를 더 소중히 여긴다.
    </label>
  </div>

  <!-- D축: Herbal vs Spicy (3문항) -->
  <div class="question">
    <p>D-1. </p>
    <label>
      <input type="radio" name="D1" value="H" />
      (1) 허브티나 아로마 오일 같은 힐링 아이템을 자주 찾는다.
    </label><br>
    <label>
      <input type="radio" name="D1" value="Sp" />
      (2) 매운 음식, 톡톡 튀는 자극으로 활력을 얻는다.
    </label>
  </div>

  <div class="question">
    <p>D-2. </p>
    <label>
      <input type="radio" name="D2" value="H" />
      (1) 마음이 복잡할 때 자연친화적인 방식(식물 키우기, 티테라피)을 선호한다.
    </label><br>
    <label>
      <input type="radio" name="D2" value="Sp" />
      (2) 색다른 취미나 강렬한 스포츠처럼 도전적인 방식을 택한다.
    </label>
  </div>

  <div class="question">
    <p>D-3. </p>
    <label>
      <input type="radio" name="D3" value="H" />
      (1) 자극이 적어도 안정된 환경이 더 좋다.
    </label><br>
    <label>
      <input type="radio" name="D3" value="Sp" />
      (2) 알싸한 긴장감이 있어야 오히려 의욕이 생긴다.
    </label>
  </div>

  <button onclick="calculateResult()">결과 보기</button>

  <!-- 결과를 표시할 영역 -->
  <div id="resultArea" class="result" style="display: none;">
    <h2>당신의 향 MBTI 결과</h2>
    <p id="typeResult"></p>
    <p id="descResult"></p>
  </div>

  <script>
    // 유형별 해석을 미리 정리해둔 객체 (예시)
    const typeDescriptions = {
      "F-F-C-H": "밝고 화사하며 상큼한 향을 좋아하는 타입. 허브의 편안함도 선호.",
      "F-F-C-Sp": "화사+상큼+알싸한 향에 끌리는 로맨틱한 모험가 타입.",
      "F-F-S-H": "경쾌하고 달콤하며 편안함을 함께 추구하는 타입.",
      "F-F-S-Sp": "로맨틱하면서도 스파이스가 주는 짜릿함을 원하는 타입.",
      "F-W-C-H": "상쾌+우디+허브 조합을 선호하는 자연친화적 타입.",
      "F-W-C-Sp": "산뜻하지만 은근히 톡 쏘는 매력의 향을 좋아함.",
      "F-W-S-H": "밝고 유쾌하면서 달콤하고 차분한 분위기도 즐기는 타입.",
      "F-W-S-Sp": "가볍고 달콤한 베이스에 스파이시 포인트를 더한 독특함 선호.",
      "D-F-C-H": "깊이 있으면서도 화사·상큼함을 놓치지 않는 균형형.",
      "D-F-C-Sp": "진중한 분위기에 시트러스와 스파이스가 어우러진 매력.",
      "D-F-S-H": "섬세하고 부드러우며 달콤+안정감을 중시하는 타입.",
      "D-F-S-Sp": "로맨틱+달콤함, 거기에 스파이시한 자극을 더한 매혹형.",
      "D-W-C-H": "묵직한 우디 베이스에 시트러스+허브가 더해진 차분한 힐링형.",
      "D-W-C-Sp": "깊고 차분하면서도 알싸한 포인트로 활력을 원하는 타입.",
      "D-W-S-H": "포근하고 편안한 우디+스위트에 허브로 안정을 추구하는 타입.",
      "D-W-S-Sp": "묵직하고 달콤하되 스파이스가 주는 강렬함에 매력을 느끼는 타입."
    };

    function calculateResult() {
      // 각 축에서 (1)번 선택 여부에 따라 점수 누적
      // A축: F vs D
      // B축: Fl vs W
      // C축: Ci vs Sw
      // D축: H vs Sp

      // 점수용 변수
      let A_F = 0, A_D = 0;
      let B_Fl = 0, B_W = 0;
      let C_Ci = 0, C_Sw = 0;
      let D_H = 0, D_Sp = 0;

      // A1, A2, A3
      const A1 = document.querySelector('input[name="A1"]:checked');
      const A2 = document.querySelector('input[name="A2"]:checked');
      const A3 = document.querySelector('input[name="A3"]:checked');

      // 만약 체크가 안 된 질문이 있으면 얼리 리턴
      if(!A1 || !A2 || !A3){
        alert("A축 질문에 모두 답해주세요.");
        return;
      }

      if(A1.value === 'F') A_F++; else A_D++;
      if(A2.value === 'F') A_F++; else A_D++;
      if(A3.value === 'F') A_F++; else A_D++;

      // B1, B2, B3
      const B1 = document.querySelector('input[name="B1"]:checked');
      const B2 = document.querySelector('input[name="B2"]:checked');
      const B3 = document.querySelector('input[name="B3"]:checked');
      if(!B1 || !B2 || !B3){
        alert("B축 질문에 모두 답해주세요.");
        return;
      }
      if(B1.value === 'Fl') B_Fl++; else B_W++;
      if(B2.value === 'Fl') B_Fl++; else B_W++;
      if(B3.value === 'Fl') B_Fl++; else B_W++;

      // C1, C2, C3
      const C1 = document.querySelector('input[name="C1"]:checked');
      const C2 = document.querySelector('input[name="C2"]:checked');
      const C3 = document.querySelector('input[name="C3"]:checked');
      if(!C1 || !C2 || !C3){
        alert("C축 질문에 모두 답해주세요.");
        return;
      }
      if(C1.value === 'Ci') C_Ci++; else C_Sw++;
      if(C2.value === 'Ci') C_Ci++; else C_Sw++;
      if(C3.value === 'Ci') C_Ci++; else C_Sw++;

      // D1, D2, D3
      const D1 = document.querySelector('input[name="D1"]:checked');
      const D2 = document.querySelector('input[name="D2"]:checked');
      const D3 = document.querySelector('input[name="D3"]:checked');
      if(!D1 || !D2 || !D3){
        alert("D축 질문에 모두 답해주세요.");
        return;
      }
      if(D1.value === 'H') D_H++; else D_Sp++;
      if(D2.value === 'H') D_H++; else D_Sp++;
      if(D3.value === 'H') D_H++; else D_Sp++;

      // 최종 A축 결과
      const A_result = (A_F >= A_D) ? 'F' : 'D'; 
      // 최종 B축 결과
      const B_result = (B_Fl >= B_W) ? 'F' : 'W';  // 여기서 F는 Floral, W는 Woody
      // 최종 C축 결과
      const C_result = (C_Ci >= C_Sw) ? 'C' : 'S'; // 여기서 C는 Citrus, S는 Sweet
      // 최종 D축 결과
      const D_result = (D_H >= D_Sp) ? 'H' : 'Sp';

      // A_result: F or D
      // B_result: F(Fl) or W
      // C_result: C(Ci) or S(Sw)
      // D_result: H or Sp

      // 이 값을 이어 붙여서 typeKey 생성
      // 예: F-F-C-H, D-W-S-Sp ...
      let typeKey = "";

      // A
      typeKey += (A_result === 'F') ? "F-" : "D-";

      // B
      if(B_result === "F") {
        // Floral인 경우 표기를 "F"가 중복되니 "F" 대신 "F(Fl)" 하거나
        // 문자열 예시는 "F-F" 형태로 중복될 수 있으므로 구분 위해 다음처럼 처리
        typeKey += "F";
      } else {
        typeKey += "W";
      }
      typeKey += "-";

      // C
      if(C_result === "C") {
        typeKey += "C";
      } else {
        typeKey += "S";
      }
      typeKey += "-";

      // D
      typeKey += (D_result === "H") ? "H" : "Sp";

      // typeKey 예) "F-F-C-H", "D-W-S-Sp"

      // 결과 표시
      document.getElementById("typeResult").textContent = typeKey;

      // typeDescriptions 에 해당하는 값이 있으면 표시, 없으면 기본 문구
      const desc = typeDescriptions[typeKey] 
                || "아직 준비되지 않은 유형이네요. 직접 해석해보세요!";
      document.getElementById("descResult").textContent = desc;

      // 결과 영역 보이기
      document.getElementById("resultArea").style.display = "block";
      // 페이지 맨 아래로 스크롤
      window.scrollTo(0, document.body.scrollHeight);
    }
  </script>
</body>
</html>
