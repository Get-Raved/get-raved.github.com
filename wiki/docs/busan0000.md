# 부산 프리깃 및 구축함
<div class="update">
updated : 2021-03-25 17:40:37
</div>

<img src=../images/parenticon.png" alt="상위 문서 아이콘" id="imagemiddle">  [중립 테크 트리](neutraltree)

***

목차
* TOC
{:toc}

***

{% include template-techtree.html %}

## 1. 계통도

<table class="busantree">
	<tr>
		<th rowspan="4">FF. Frigate-01 (1레벨)</th>
		<td rowspan="4">↔</td>
		<th>FF. Frigate-01 M1 (2레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-01 M2 (2레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-01 M3 (2레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-11 (14레벨)</th>
	</tr>
	<tr>
		<td>↓</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th rowspan="4">FF. Frigate-02 (3레벨)</th>
		<td rowspan="4">↔</td>
		<th>FF. Frigate-02 M1 (4레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-02 M2 (4레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-02 M3 (4레벨)</th>
	</tr>
	<tr>
		<th>FF. Frigate-21 (21레벨)</th>
	</tr>
	<tr>
		<td>↓</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th rowspan="3">DD. Destroyer-01 (5레벨)</th>
		<td rowspan="3">↔</td>
		<th>DD. Destroyer-01 M1 (6레벨)</th>
	</tr>
	<tr>
		<th>DD. Destroyer-01 M2 (6레벨)</th>
	</tr>
	<tr>
		<th>DD. Destroyer-01 M3 (6레벨)</th>
	</tr>
	<tr>
		<td>↓</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th rowspan="3">DD. Destroyer-02 (9레벨)</th>
		<td rowspan="3">↔</td>
		<th>DD. Destroyer-02 M1 (10레벨)</th>
	</tr>
	<tr>
		<th>DD. Destroyer-02 M2 (10레벨)</th>
	</tr>
	<tr>
		<th>DD. Destroyer-02 M3 (10레벨)</th>
	</tr>
	<tr>
		<td>↓</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>FF. Frigate-X (22레벨)</th>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td>↓</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<th>FF. Frigate-Y (25레벨)</th>
		<td></td>
		<td></td>
	</tr>
</table>

## 2. 함선 목록

### 2.1. Frigate-01 (1레벨)

<img src="../images/Frigate-01.gif" alt="frigate-01.gif">

<details>
<summary>함선 기본 스펙 펼치기/접기</summary>
<p>
<table class="busanspec">
	<tr>
		<th>DP</th>
		<td>4800</td>
	</tr>
	<tr>
		<th>탑승 레벨</th>
		<td>1</td>
	</tr>
	<tr>
		<th>기본 배수량</th>
		<td>1122</td>
	</tr>
	<tr>
		<th>만재 배수량</th>
		<td>1600</td>
	</tr>
	<tr>
		<th>선회력</th>
		<td>38</td>
	</tr>
	<tr>
		<th>대미지 감소</th>
		<td>3%</td>
	</tr>
	<tr>
		<th>최대 피격 AP 대미지</th>
		<td>96</td>
	</tr>
	<tr>
		<th>함재기 동시발진 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>함재기 용적</th>
		<td>0</td>
	</tr>
	<tr>
		<th>주포병 수</th>
		<td>2</td>
	</tr>
	<tr>
		<th>부포병 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>보조병 수</th>
		<td>1</td>
	</tr>
	<tr>
		<th>가격</th>
		<td>30</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>함포 배치 펼치기/접기</summary>
<p>
<table class="gunarrange">
	<tr>
		<th colspan="5">전방</th>
	</tr>
	<tr>
		<th rowspan="4">좌현</th>
		<td></td>
		<td id="frontmaingun">26</td>
		<td></td>
		<th rowspan="4">우현</th>
	</tr>
	<tr>
		<td></td>
		<th>함교</th>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">26</td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">26</td>
		<td></td>
	</tr>
	<tr>
		<th colspan="5">후방</th>
	</tr>
</table>

<table>
	<tr>
		<td id="frontmaingun"></td>
		<td>전방 주포</td>
		<td id="rearmaingun"></td>
		<td>후방 주포</td>
		<td id="frontsubgun"></td>
		<td>전방 부포</td>
		<td id="rearsubgun"></td>
		<td>후방 부포</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>주요 컴포넌트 펼치기/접기</summary>
<p>
<table class="busancomponents">
	<tr>
		<th>주요 주포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>3"/40 cal Mark ZII</td>
		<td>1</td>
		<td>500</td>
		<td>70</td>
		<td></td>
		<td>802</td>
		<td>1.28</td>
		<td>6.836</td>
		<td>1</td>
		<td>일반수병</td>
	</tr>
</table>	

<table class="busancomponents">
	<tr>
		<th>주요 부포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 어뢰 발사관</th>
		<th rowspan="2">최대 어뢰 수</th>
		<th rowspan="2">기본 연사 속도(초)</th>
		<th colspan="2">어뢰 속도</th>
		<th colspan="2">어뢰 사정거리</th>
		<th rowspan="2">무게(톤)</th>
		<th rowspan="2">제한 레벨</th>
		<th rowspan="2">필요 병종</th>
	</tr>
	<tr>
		<th>저속</th>
		<th>고속</th>
		<th>저속</th>
		<th>고속</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 엔진</th>
		<th colspan="2">만재 배수량 기준</th>
		<th rowspan="2">오버힛 지속시간(초)</th>
		<th rowspan="2">오버힛 가능 최소 DP</th>
		<th rowspan="2">무게(톤)</th>
	</tr>
	<tr>
		<th>기본 속력</th>
		<th>최대 속력</th>	
	</tr>
	<tr>
		<td>FF Engine I (Heavy)</td>
		<td>42</td>
		<td>51</td>
		<td>7</td>
		<td>1920</td>
		<td>110</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th>FCS</th>
		<th>명중 보너스</th>
		<th>착탄 보정 거리</th>
		<th>어뢰 탐지 거리</th>
		<th>무게(톤)</th>
	</tr>
	<tr>
		<td>FF FCS I (Aiming)</td>
		<td>55</td>
		<td>800</td>
		<td>700</td>
		<td>70</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">함재기</th>
		<th rowspan="2">용적</th>
		<th rowspan="2">최대 탑재 수</th>
		<th rowspan="2">레벨</th>
		<th rowspan="2">DP</th>
		<th colspan="2">방어력</th>
		<th rowspan="2">속력</th>
		<th rowspan="2">시야</th>
		<th colspan="2">공격력</th>
		<th rowspan="2">체공시간(초)</th>
		<th rowspan="2">준비 시간</th>
	</tr>
	<tr>
		<th>AP</th>
		<th>HE</th>
		<th>대함</th>
		<th>공대공</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
</p>
</details>

<div class="paratitle">
개요
</div>

네이비필드에서 최초로 탑승할 수 있는 함선이다.

#### 2.1.1. Frigate-01 M1 (2레벨)

<img src="../images/Frigate-01-M1.gif" alt="Frigate-01-M1.gif">

<details>
<summary>함선 기본 스펙 펼치기/접기</summary>
<p>
<table class="busanspec">
	<tr>
		<th>DP</th>
		<td>4300</td>
	</tr>
	<tr>
		<th>탑승 레벨</th>
		<td>2</td>
	</tr>
	<tr>
		<th>기본 배수량</th>
		<td>1122</td>
	</tr>
	<tr>
		<th>만재 배수량</th>
		<td>1600</td>
	</tr>
	<tr>
		<th>선회력</th>
		<td>38</td>
	</tr>
	<tr>
		<th>대미지 감소</th>
		<td>2.4%</td>
	</tr>
	<tr>
		<th>최대 피격 AP 대미지</th>
		<td>96</td>
	</tr>
	<tr>
		<th>함재기 동시발진 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>함재기 용적</th>
		<td>0</td>
	</tr>
	<tr>
		<th>주포병 수</th>
		<td>2</td>
	</tr>
	<tr>
		<th>부포병 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>보조병 수</th>
		<td>1</td>
	</tr>
	<tr>
		<th>가격</th>
		<td>30</td>
	</tr>
	<tr>
		<th>개장 비용</th>
		<td>0</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>함포 배치 펼치기/접기</summary>
<p>
<table class="gunarrange">
	<tr>
		<th colspan="5">전방</th>
	</tr>
	<tr>
		<th rowspan="4">좌현</th>
		<td></td>
		<td id="frontmaingun">29</td>
		<td></td>
		<th rowspan="4">우현</th>
	</tr>
	<tr>
		<td></td>
		<th>함교</th>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">29</td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">29</td>
		<td></td>
	</tr>
	<tr>
		<th colspan="5">후방</th>
	</tr>
</table>

<table>
	<tr>
		<td id="frontmaingun"></td>
		<td>전방 주포</td>
		<td id="rearmaingun"></td>
		<td>후방 주포</td>
		<td id="frontsubgun"></td>
		<td>전방 부포</td>
		<td id="rearsubgun"></td>
		<td>후방 부포</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>주요 컴포넌트 펼치기/접기</summary>
<p>
<table class="busancomponents">
	<tr>
		<th>주요 주포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>3"/40 cal Mark ZII L</td>
		<td>1</td>
		<td>550</td>
		<td>70</td>
		<td></td>
		<td>884</td>
		<td>1.4</td>
		<td>7.52</td>
		<td>2</td>
		<td>일반수병</td>
	</tr>
</table>	

<table class="busancomponents">
	<tr>
		<th>주요 부포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 어뢰 발사관</th>
		<th rowspan="2">최대 어뢰 수</th>
		<th rowspan="2">기본 연사 속도(초)</th>
		<th colspan="2">어뢰 속도</th>
		<th colspan="2">어뢰 사정거리</th>
		<th rowspan="2">무게(톤)</th>
		<th rowspan="2">제한 레벨</th>
		<th rowspan="2">필요 병종</th>
	</tr>
	<tr>
		<th>저속</th>
		<th>고속</th>
		<th>저속</th>
		<th>고속</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 엔진</th>
		<th colspan="2">만재 배수량 기준</th>
		<th rowspan="2">오버힛 지속시간(초)</th>
		<th rowspan="2">오버힛 가능 최소 DP</th>
		<th rowspan="2">무게(톤)</th>
	</tr>
	<tr>
		<th>기본 속력</th>
		<th>최대 속력</th>	
	</tr>
	<tr>
		<td>FF Engine I (Heavy)</td>
		<td>42</td>
		<td>51</td>
		<td>7</td>
		<td>1720</td>
		<td>110</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th>FCS</th>
		<th>명중 보너스</th>
		<th>착탄 보정 거리</th>
		<th>어뢰 탐지 거리</th>
		<th>무게(톤)</th>
	</tr>
	<tr>
		<td>FF FCS II (Aiming)</td>
		<td>58</td>
		<td>750</td>
		<td>750</td>
		<td>78</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">함재기</th>
		<th rowspan="2">용적</th>
		<th rowspan="2">최대 탑재 수</th>
		<th rowspan="2">레벨</th>
		<th rowspan="2">DP</th>
		<th colspan="2">방어력</th>
		<th rowspan="2">속력</th>
		<th rowspan="2">시야</th>
		<th colspan="2">공격력</th>
		<th rowspan="2">체공시간(초)</th>
		<th rowspan="2">준비 시간</th>
	</tr>
	<tr>
		<th>AP</th>
		<th>HE</th>
		<th>대함</th>
		<th>공대공</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
</p>
</details>

<div class="paratitle">
개요
</div>

Frigate-01의 화력 강화형. DP가 감소하고 주포와 FCS의 용적이 상승하였다.

#### 2.1.1. Frigate-01 M2 (2레벨)

<img src="../images/Frigate-01-M2.gif" alt="Frigate-01-M2.gif">

<details>
<summary>함선 기본 스펙 펼치기/접기</summary>
<p>
<table class="busanspec">
	<tr>
		<th>DP</th>
		<td>5300</td>
	</tr>
	<tr>
		<th>탑승 레벨</th>
		<td>2</td>
	</tr>
	<tr>
		<th>기본 배수량</th>
		<td>1122</td>
	</tr>
	<tr>
		<th>만재 배수량</th>
		<td>1600</td>
	</tr>
	<tr>
		<th>선회력</th>
		<td>30</td>
	</tr>
	<tr>
		<th>대미지 감소</th>
		<td>3.6%</td>
	</tr>
	<tr>
		<th>최대 피격 AP 대미지</th>
		<td>96</td>
	</tr>
	<tr>
		<th>함재기 동시발진 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>함재기 용적</th>
		<td>0</td>
	</tr>
	<tr>
		<th>주포병 수</th>
		<td>2</td>
	</tr>
	<tr>
		<th>부포병 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>보조병 수</th>
		<td>1</td>
	</tr>
	<tr>
		<th>가격</th>
		<td>30</td>
	</tr>
	<tr>
		<th>개장 비용</th>
		<td>0</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>함포 배치 펼치기/접기</summary>
<p>
<table class="gunarrange">
	<tr>
		<th colspan="5">전방</th>
	</tr>
	<tr>
		<th rowspan="4">좌현</th>
		<td></td>
		<td id="frontmaingun">26</td>
		<td></td>
		<th rowspan="4">우현</th>
	</tr>
	<tr>
		<td></td>
		<th>함교</th>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">26</td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">26</td>
		<td></td>
	</tr>
	<tr>
		<th colspan="5">후방</th>
	</tr>
</table>

<table>
	<tr>
		<td id="frontmaingun"></td>
		<td>전방 주포</td>
		<td id="rearmaingun"></td>
		<td>후방 주포</td>
		<td id="frontsubgun"></td>
		<td>전방 부포</td>
		<td id="rearsubgun"></td>
		<td>후방 부포</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>주요 컴포넌트 펼치기/접기</summary>
<p>
<table class="busancomponents">
	<tr>
		<th>주요 주포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>3"/40 cal Mark ZII L</td>
		<td>1</td>
		<td>450</td>
		<td>70</td>
		<td></td>
		<td>884</td>
		<td>1.4</td>
		<td>7.52</td>
		<td>2</td>
		<td>일반수병</td>
	</tr>
</table>	

<table class="busancomponents">
	<tr>
		<th>주요 부포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 어뢰 발사관</th>
		<th rowspan="2">최대 어뢰 수</th>
		<th rowspan="2">기본 연사 속도(초)</th>
		<th colspan="2">어뢰 속도</th>
		<th colspan="2">어뢰 사정거리</th>
		<th rowspan="2">무게(톤)</th>
		<th rowspan="2">제한 레벨</th>
		<th rowspan="2">필요 병종</th>
	</tr>
	<tr>
		<th>저속</th>
		<th>고속</th>
		<th>저속</th>
		<th>고속</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 엔진</th>
		<th colspan="2">만재 배수량 기준</th>
		<th rowspan="2">오버힛 지속시간(초)</th>
		<th rowspan="2">오버힛 가능 최소 DP</th>
		<th rowspan="2">무게(톤)</th>
	</tr>
	<tr>
		<th>기본 속력</th>
		<th>최대 속력</th>	
	</tr>
	<tr>
		<td>FF Engine I (Heavy)</td>
		<td>42</td>
		<td>46</td>
		<td>7</td>
		<td>2120</td>
		<td>110</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th>FCS</th>
		<th>명중 보너스</th>
		<th>착탄 보정 거리</th>
		<th>어뢰 탐지 거리</th>
		<th>무게(톤)</th>
	</tr>
	<tr>
		<td>FF FCS I (Aiming)</td>
		<td>55</td>
		<td>800</td>
		<td>700</td>
		<td>70</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">함재기</th>
		<th rowspan="2">용적</th>
		<th rowspan="2">최대 탑재 수</th>
		<th rowspan="2">레벨</th>
		<th rowspan="2">DP</th>
		<th colspan="2">방어력</th>
		<th rowspan="2">속력</th>
		<th rowspan="2">시야</th>
		<th colspan="2">공격력</th>
		<th rowspan="2">체공시간(초)</th>
		<th rowspan="2">준비 시간</th>
	</tr>
	<tr>
		<th>AP</th>
		<th>HE</th>
		<th>대함</th>
		<th>공대공</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
</p>
</details>

<div class="paratitle">
개요
</div>

Frigate-01의 방어력 강화형. 기동성이 감소하고 DP가 상승하였다.

#### 2.1.1. Frigate-01 M3 (2레벨)

<img src="../images/Frigate-01-M3.gif" alt="Frigate-01-M3.gif">

<details>
<summary>함선 기본 스펙 펼치기/접기</summary>
<p>
<table class="busanspec">
	<tr>
		<th>DP</th>
		<td>4800</td>
	</tr>
	<tr>
		<th>탑승 레벨</th>
		<td>2</td>
	</tr>
	<tr>
		<th>기본 배수량</th>
		<td>1122</td>
	</tr>
	<tr>
		<th>만재 배수량</th>
		<td>1600</td>
	</tr>
	<tr>
		<th>선회력</th>
		<td>46</td>
	</tr>
	<tr>
		<th>대미지 감소</th>
		<td>3%</td>
	</tr>
	<tr>
		<th>최대 피격 AP 대미지</th>
		<td>96</td>
	</tr>
	<tr>
		<th>함재기 동시발진 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>함재기 용적</th>
		<td>0</td>
	</tr>
	<tr>
		<th>주포병 수</th>
		<td>2</td>
	</tr>
	<tr>
		<th>부포병 수</th>
		<td>0</td>
	</tr>
	<tr>
		<th>보조병 수</th>
		<td>1</td>
	</tr>
	<tr>
		<th>가격</th>
		<td>30</td>
	</tr>
	<tr>
		<th>개장 비용</th>
		<td>0</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>함포 배치 펼치기/접기</summary>
<p>
<table class="gunarrange">
	<tr>
		<th colspan="5">전방</th>
	</tr>
	<tr>
		<th rowspan="4">좌현</th>
		<td></td>
		<td id="frontmaingun">23</td>
		<td></td>
		<th rowspan="4">우현</th>
	</tr>
	<tr>
		<td></td>
		<th>함교</th>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">23</td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td id="rearmaingun">23</td>
		<td></td>
	</tr>
	<tr>
		<th colspan="5">후방</th>
	</tr>
</table>

<table>
	<tr>
		<td id="frontmaingun"></td>
		<td>전방 주포</td>
		<td id="rearmaingun"></td>
		<td>후방 주포</td>
		<td id="frontsubgun"></td>
		<td>전방 부포</td>
		<td id="rearsubgun"></td>
		<td>후방 부포</td>
	</tr>
</table>
</p>
</details>

<details>
<summary>주요 컴포넌트 펼치기/접기</summary>
<p>
<table class="busancomponents">
	<tr>
		<th>주요 주포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>3"/40 cal Mark ZII L</td>
		<td>1</td>
		<td>350</td>
		<td>70</td>
		<td></td>
		<td>884</td>
		<td>1.4</td>
		<td>7.52</td>
		<td>2</td>
		<td>일반수병</td>
	</tr>
</table>	

<table class="busancomponents">
	<tr>
		<th>주요 부포</th>
		<th>포문 수</th>
		<th>최대 사격 횟수</th>
		<th>최대 고각</th>
		<th>황금각</th>
		<th>사정거리</th>
		<th>기본 연사 속도(초)</th>
		<th>무게(톤)</th>
		<th>제한 레벨</th>
		<th>필요 병종</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 어뢰 발사관</th>
		<th rowspan="2">최대 어뢰 수</th>
		<th rowspan="2">기본 연사 속도(초)</th>
		<th colspan="2">어뢰 속도</th>
		<th colspan="2">어뢰 사정거리</th>
		<th rowspan="2">무게(톤)</th>
		<th rowspan="2">제한 레벨</th>
		<th rowspan="2">필요 병종</th>
	</tr>
	<tr>
		<th>저속</th>
		<th>고속</th>
		<th>저속</th>
		<th>고속</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">주요 엔진</th>
		<th colspan="2">만재 배수량 기준</th>
		<th rowspan="2">오버힛 지속시간(초)</th>
		<th rowspan="2">오버힛 가능 최소 DP</th>
		<th rowspan="2">무게(톤)</th>
	</tr>
	<tr>
		<th>기본 속력</th>
		<th>최대 속력</th>	
	</tr>
	<tr>
		<td>FF Engine I (Heavy)</td>
		<td>42</td>
		<td>56</td>
		<td>7</td>
		<td>1920</td>
		<td>110</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th>FCS</th>
		<th>명중 보너스</th>
		<th>착탄 보정 거리</th>
		<th>어뢰 탐지 거리</th>
		<th>무게(톤)</th>
	</tr>
	<tr>
		<td>FF FCS I (Aiming)</td>
		<td>55</td>
		<td>800</td>
		<td>700</td>
		<td>70</td>
	</tr>
</table>

<table class="busancomponents">
	<tr>
		<th rowspan="2">함재기</th>
		<th rowspan="2">용적</th>
		<th rowspan="2">최대 탑재 수</th>
		<th rowspan="2">레벨</th>
		<th rowspan="2">DP</th>
		<th colspan="2">방어력</th>
		<th rowspan="2">속력</th>
		<th rowspan="2">시야</th>
		<th colspan="2">공격력</th>
		<th rowspan="2">체공시간(초)</th>
		<th rowspan="2">준비 시간</th>
	</tr>
	<tr>
		<th>AP</th>
		<th>HE</th>
		<th>대함</th>
		<th>공대공</th>
	</tr>
	<tr>
		<td>없음</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
</p>
</details>

<div class="paratitle">
개요
</div>

Frigate-01의 기동력 강화형. 화력이 감소하고 선회능력과 오버힛 속도가 상승하였다.
