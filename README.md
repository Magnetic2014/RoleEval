# RoleEval: A Bilingual Role Evaluation Benchmark for Large Language Models

We introduce RoleEval, a bilingual benchmark designed to assess the memorization, utilization, and reasoning capabilities of role knowledge. RoleEval comprises *RoleEval-Global* (including internationally recognized characters) and *RoleEval-Chinese* (including characters popular in China), with 6,000 Chinese-English parallel multiple-choice questions focusing on 300 influential people and fictional characters drawn from a variety of domains including celebrities, anime, comics, movies, TV series, games, and fiction. These questions cover basic knowledge and multi-hop reasoning abilities, aiming to systematically probe various aspects such as personal information, relationships, abilities, and experiences of the characters. To maintain high standards, we perform a hybrid quality check process combining automatic and human verification, ensuring that the questions are diverse, challenging, and discriminative.

**NOTE: The English version of RoleEval is under internal review and will be released later.**

## Leaderboard (5-shot)

If you want to submit your model's predictions to our leaderboard, please feel free to contact us via thshen@tju.edu.cn for more details.

**NOTE:**
1. **Models below are sorted by the weighted average of the accuracy of RoleEval-Global and RoleEval-Chinese.**
2. **\* indicates the results calculated by submitted predictions.**

### RoleEval (zh)

<table cellspacing="0" border="0">
	<colgroup width="211"></colgroup>
	<colgroup span="2" width="50"></colgroup>
	<colgroup width="51"></colgroup>
	<colgroup span="5" width="50"></colgroup>
	<colgroup width="51"></colgroup>
	<colgroup span="2" width="50"></colgroup>
	<colgroup width="54"></colgroup>
	<tr>
		<td rowspan=2 height="43" align="center" valign=middle><b><font color="#000000">Model</font></b></td>
		<td colspan=6 align="center" valign=middle><b><font color="#000000">RoleEval-Global (4,000 questions)</font></b></td>
		<td colspan=6 align="center" valign=middle><b><font color="#000000">RoleEval-Chinese (2,000 questions)</font></b></td>
		</tr>
	<tr>
		<td align="center" valign=middle><b><font color="#000000">Celebrities</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Anime and Comics</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Movies and TV Series</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Games</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Fiction</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Avg.</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Celebrities</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Anime and Comics</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Movies and TV Series</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Games</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Fiction</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Avg.</font></b></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-4-1106</font></b></td>
		<td align="center" valign=middle sdval="74.75" sdnum="1033;0;0.00"><b><font color="#000000">74.75</font></b></td>
		<td align="center" valign=middle sdval="73.62" sdnum="1033;0;0.00"><b><font color="#000000">73.62</font></b></td>
		<td align="center" valign=middle sdval="74.38" sdnum="1033;0;0.00"><b><font color="#000000">74.38</font></b></td>
		<td align="center" valign=middle sdval="72.5" sdnum="1033;0;0.00"><b><font color="#000000">72.50</font></b></td>
		<td align="center" valign=middle sdval="71.62" sdnum="1033;0;0.00"><font color="#000000">71.62</font></td>
		<td align="center" valign=middle sdval="73.38" sdnum="1033;0;0.00"><b><font color="#000000">73.38</font></b></td>
		<td align="center" valign=middle sdval="62.5" sdnum="1033;0;0.00"><font color="#000000">62.50</font></td>
		<td align="center" valign=middle sdval="63.25" sdnum="1033;0;0.00"><b><font color="#000000">63.25</font></b></td>
		<td align="center" valign=middle sdval="63" sdnum="1033;0;0.00"><font color="#000000">63.00</font></td>
		<td align="center" valign=middle sdval="62" sdnum="1033;0;0.00"><b><font color="#000000">62.00</font></b></td>
		<td align="center" valign=middle sdval="63" sdnum="1033;0;0.00"><font color="#000000">63.00</font></td>
		<td align="center" valign=middle sdval="62.75" sdnum="1033;0;0.00"><font color="#000000">62.75</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-4-0613</font></b></td>
		<td align="center" valign=middle sdval="73.38" sdnum="1033;0;0.00"><font color="#000000">73.38</font></td>
		<td align="center" valign=middle sdval="72.12" sdnum="1033;0;0.00"><font color="#000000">72.12</font></td>
		<td align="center" valign=middle sdval="74.25" sdnum="1033;0;0.00"><font color="#000000">74.25</font></td>
		<td align="center" valign=middle sdval="72.25" sdnum="1033;0;0.00"><font color="#000000">72.25</font></td>
		<td align="center" valign=middle sdval="69.62" sdnum="1033;0;0.00"><font color="#000000">69.62</font></td>
		<td align="center" valign=middle sdval="72.32" sdnum="1033;0;0.00"><font color="#000000">72.32</font></td>
		<td align="center" valign=middle sdval="57.75" sdnum="1033;0;0.00"><font color="#000000">57.75</font></td>
		<td align="center" valign=middle sdval="60.25" sdnum="1033;0;0.00"><font color="#000000">60.25</font></td>
		<td align="center" valign=middle sdval="57.75" sdnum="1033;0;0.00"><font color="#000000">57.75</font></td>
		<td align="center" valign=middle sdval="60" sdnum="1033;0;0.00"><font color="#000000">60.00</font></td>
		<td align="center" valign=middle sdval="58" sdnum="1033;0;0.00"><font color="#000000">58.00</font></td>
		<td align="center" valign=middle sdval="58.75" sdnum="1033;0;0.00"><font color="#000000">58.75</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-72B</font></b></td>
		<td align="center" valign=middle sdval="72.88" sdnum="1033;0;0.00"><font color="#000000">72.88</font></td>
		<td align="center" valign=middle sdval="63.88" sdnum="1033;0;0.00"><font color="#000000">63.88</font></td>
		<td align="center" valign=middle sdval="70.38" sdnum="1033;0;0.00"><font color="#000000">70.38</font></td>
		<td align="center" valign=middle sdval="56.75" sdnum="1033;0;0.00"><font color="#000000">56.75</font></td>
		<td align="center" valign=middle sdval="73.5" sdnum="1033;0;0.00"><b><font color="#000000">73.50</font></b></td>
		<td align="center" valign=middle sdval="67.47" sdnum="1033;0;0.00"><font color="#000000">67.47</font></td>
		<td align="center" valign=middle sdval="70" sdnum="1033;0;0.00"><b><font color="#000000">70.00</font></b></td>
		<td align="center" valign=middle sdval="59.75" sdnum="1033;0;0.00"><font color="#000000">59.75</font></td>
		<td align="center" valign=middle sdval="66" sdnum="1033;0;0.00"><font color="#000000">66.00</font></td>
		<td align="center" valign=middle sdval="61.25" sdnum="1033;0;0.00"><font color="#000000">61.25</font></td>
		<td align="center" valign=middle sdval="74" sdnum="1033;0;0.00"><font color="#000000">74.00</font></td>
		<td align="center" valign=middle sdval="66.2" sdnum="1033;0;0.00"><b><font color="#000000">66.20</font></b></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-Character-Turbo*</font></b></td>
		<td align="center" valign=middle sdval="72.88" sdnum="1033;0;0.00"><font color="#000000">72.25</font></td>
		<td align="center" valign=middle sdval="63.88" sdnum="1033;0;0.00"><font color="#000000">65.25</font></td>
		<td align="center" valign=middle sdval="70.38" sdnum="1033;0;0.00"><font color="#000000">64.62</font></td>
		<td align="center" valign=middle sdval="56.75" sdnum="1033;0;0.00"><font color="#000000">55.50</font></td>
		<td align="center" valign=middle sdval="73.5" sdnum="1033;0;0.00"><font color="#000000">72.75</font></td>
		<td align="center" valign=middle sdval="67.47" sdnum="1033;0;0.00"><font color="#000000">66.07</font></td>
		<td align="center" valign=middle sdval="70" sdnum="1033;0;0.00"><font color="#000000">66.25</font></td>
		<td align="center" valign=middle sdval="59.75" sdnum="1033;0;0.00"><font color="#000000">61.00</font></td>
		<td align="center" valign=middle sdval="66" sdnum="1033;0;0.00"><b><font color="#000000">71.50</font></b></td>
		<td align="center" valign=middle sdval="61.25" sdnum="1033;0;0.00"><font color="#000000">54.25</font></td>
		<td align="center" valign=middle sdval="74" sdnum="1033;0;0.00"><font color="#000000">76.25</font></td>
		<td align="center" valign=middle sdval="66.2" sdnum="1033;0;0.00"><font color="#000000">65.85</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Yi-34B</font></b></td>
		<td align="center" valign=middle sdval="72.38" sdnum="1033;0;0.00"><font color="#000000">72.38</font></td>
		<td align="center" valign=middle sdval="60.62" sdnum="1033;0;0.00"><font color="#000000">60.62</font></td>
		<td align="center" valign=middle sdval="69.75" sdnum="1033;0;0.00"><font color="#000000">69.75</font></td>
		<td align="center" valign=middle sdval="53.25" sdnum="1033;0;0.00"><font color="#000000">53.25</font></td>
		<td align="center" valign=middle sdval="73.12" sdnum="1033;0;0.00"><font color="#000000">73.12</font></td>
		<td align="center" valign=middle sdval="65.83" sdnum="1033;0;0.00"><font color="#000000">65.83</font></td>
		<td align="center" valign=middle sdval="65.5" sdnum="1033;0;0.00"><font color="#000000">65.50</font></td>
		<td align="center" valign=middle sdval="54.5" sdnum="1033;0;0.00"><font color="#000000">54.50</font></td>
		<td align="center" valign=middle sdval="70" sdnum="1033;0;0.00"><font color="#000000">70.00</font></td>
		<td align="center" valign=middle sdval="56" sdnum="1033;0;0.00"><font color="#000000">56.00</font></td>
		<td align="center" valign=middle sdval="77" sdnum="1033;0;0.00"><b><font color="#000000">77.00</font></b></td>
		<td align="center" valign=middle sdval="64.6" sdnum="1033;0;0.00"><font color="#000000">64.60</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-Character-Lite*</font></b></td>
		<td align="center" valign=middle sdval="72.38" sdnum="1033;0;0.00"><font color="#000000">60.62</font></td>
		<td align="center" valign=middle sdval="60.62" sdnum="1033;0;0.00"><font color="#000000">56.62</font></td>
		<td align="center" valign=middle sdval="69.75" sdnum="1033;0;0.00"><font color="#000000">51.88</font></td>
		<td align="center" valign=middle sdval="53.25" sdnum="1033;0;0.00"><font color="#000000">48.25</font></td>
		<td align="center" valign=middle sdval="73.12" sdnum="1033;0;0.00"><font color="#000000">62.12</font></td>
		<td align="center" valign=middle sdval="65.83" sdnum="1033;0;0.00"><font color="#000000">55.90</font></td>
		<td align="center" valign=middle sdval="65.5" sdnum="1033;0;0.00"><font color="#000000">56.00</font></td>
		<td align="center" valign=middle sdval="54.5" sdnum="1033;0;0.00"><font color="#000000">51.75</font></td>
		<td align="center" valign=middle sdval="70" sdnum="1033;0;0.00"><font color="#000000">56.75</font></td>
		<td align="center" valign=middle sdval="56" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="77" sdnum="1033;0;0.00"><font color="#000000">62.00</font></td>
		<td align="center" valign=middle sdval="64.6" sdnum="1033;0;0.00"><font color="#000000">54.80</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">MiniMax</font></b></td>
		<td align="center" valign=middle sdval="51.75" sdnum="1033;0;0.00"><font color="#000000">51.75</font></td>
		<td align="center" valign=middle sdval="54.5" sdnum="1033;0;0.00"><font color="#000000">54.50</font></td>
		<td align="center" valign=middle sdval="62.62" sdnum="1033;0;0.00"><font color="#000000">62.62</font></td>
		<td align="center" valign=middle sdval="56.75" sdnum="1033;0;0.00"><font color="#000000">56.75</font></td>
		<td align="center" valign=middle sdval="52.75" sdnum="1033;0;0.00"><font color="#000000">52.75</font></td>
		<td align="center" valign=middle sdval="55.67" sdnum="1033;0;0.00"><font color="#000000">55.67</font></td>
		<td align="center" valign=middle sdval="54" sdnum="1033;0;0.00"><font color="#000000">54.00</font></td>
		<td align="center" valign=middle sdval="55" sdnum="1033;0;0.00"><font color="#000000">55.00</font></td>
		<td align="center" valign=middle sdval="52.75" sdnum="1033;0;0.00"><font color="#000000">52.75</font></td>
		<td align="center" valign=middle sdval="57.5" sdnum="1033;0;0.00"><font color="#000000">57.50</font></td>
		<td align="center" valign=middle sdval="54" sdnum="1033;0;0.00"><font color="#000000">54.00</font></td>
		<td align="center" valign=middle sdval="54.65" sdnum="1033;0;0.00"><font color="#000000">54.65</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Yi-6B</font></b></td>
		<td align="center" valign=middle sdval="61.88" sdnum="1033;0;0.00"><font color="#000000">61.88</font></td>
		<td align="center" valign=middle sdval="51.38" sdnum="1033;0;0.00"><font color="#000000">51.38</font></td>
		<td align="center" valign=middle sdval="52.38" sdnum="1033;0;0.00"><font color="#000000">52.38</font></td>
		<td align="center" valign=middle sdval="45.38" sdnum="1033;0;0.00"><font color="#000000">45.38</font></td>
		<td align="center" valign=middle sdval="60.75" sdnum="1033;0;0.00"><font color="#000000">60.75</font></td>
		<td align="center" valign=middle sdval="54.35" sdnum="1033;0;0.00"><font color="#000000">54.35</font></td>
		<td align="center" valign=middle sdval="59.25" sdnum="1033;0;0.00"><font color="#000000">59.25</font></td>
		<td align="center" valign=middle sdval="46" sdnum="1033;0;0.00"><font color="#000000">46.00</font></td>
		<td align="center" valign=middle sdval="61.5" sdnum="1033;0;0.00"><font color="#000000">61.50</font></td>
		<td align="center" valign=middle sdval="47.75" sdnum="1033;0;0.00"><font color="#000000">47.75</font></td>
		<td align="center" valign=middle sdval="62" sdnum="1033;0;0.00"><font color="#000000">62.00</font></td>
		<td align="center" valign=middle sdval="55.3" sdnum="1033;0;0.00"><font color="#000000">55.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-14B</font></b></td>
		<td align="center" valign=middle sdval="62.5" sdnum="1033;0;0.00"><font color="#000000">62.50</font></td>
		<td align="center" valign=middle sdval="52.38" sdnum="1033;0;0.00"><font color="#000000">52.38</font></td>
		<td align="center" valign=middle sdval="55" sdnum="1033;0;0.00"><font color="#000000">55.00</font></td>
		<td align="center" valign=middle sdval="45.5" sdnum="1033;0;0.00"><font color="#000000">45.50</font></td>
		<td align="center" valign=middle sdval="58" sdnum="1033;0;0.00"><font color="#000000">58.00</font></td>
		<td align="center" valign=middle sdval="54.67" sdnum="1033;0;0.00"><font color="#000000">54.67</font></td>
		<td align="center" valign=middle sdval="56.25" sdnum="1033;0;0.00"><font color="#000000">56.25</font></td>
		<td align="center" valign=middle sdval="45.5" sdnum="1033;0;0.00"><font color="#000000">45.50</font></td>
		<td align="center" valign=middle sdval="54.75" sdnum="1033;0;0.00"><font color="#000000">54.75</font></td>
		<td align="center" valign=middle sdval="51.5" sdnum="1033;0;0.00"><font color="#000000">51.50</font></td>
		<td align="center" valign=middle sdval="56.75" sdnum="1033;0;0.00"><font color="#000000">56.75</font></td>
		<td align="center" valign=middle sdval="52.95" sdnum="1033;0;0.00"><font color="#000000">52.95</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-13B</font></b></td>
		<td align="center" valign=middle sdval="60.25" sdnum="1033;0;0.00"><font color="#000000">60.25</font></td>
		<td align="center" valign=middle sdval="52.38" sdnum="1033;0;0.00"><font color="#000000">52.38</font></td>
		<td align="center" valign=middle sdval="51" sdnum="1033;0;0.00"><font color="#000000">51.00</font></td>
		<td align="center" valign=middle sdval="46.88" sdnum="1033;0;0.00"><font color="#000000">46.88</font></td>
		<td align="center" valign=middle sdval="60.75" sdnum="1033;0;0.00"><font color="#000000">60.75</font></td>
		<td align="center" valign=middle sdval="54.25" sdnum="1033;0;0.00"><font color="#000000">54.25</font></td>
		<td align="center" valign=middle sdval="54.75" sdnum="1033;0;0.00"><font color="#000000">54.75</font></td>
		<td align="center" valign=middle sdval="47.75" sdnum="1033;0;0.00"><font color="#000000">47.75</font></td>
		<td align="center" valign=middle sdval="54" sdnum="1033;0;0.00"><font color="#000000">54.00</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="60" sdnum="1033;0;0.00"><font color="#000000">60.00</font></td>
		<td align="center" valign=middle sdval="52.8" sdnum="1033;0;0.00"><font color="#000000">52.80</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Skywork-13B</font></b></td>
		<td align="center" valign=middle sdval="59.13" sdnum="1033;0;0.00"><font color="#000000">59.13</font></td>
		<td align="center" valign=middle sdval="51.75" sdnum="1033;0;0.00"><font color="#000000">51.75</font></td>
		<td align="center" valign=middle sdval="51.88" sdnum="1033;0;0.00"><font color="#000000">51.88</font></td>
		<td align="center" valign=middle sdval="44.5" sdnum="1033;0;0.00"><font color="#000000">44.50</font></td>
		<td align="center" valign=middle sdval="58.75" sdnum="1033;0;0.00"><font color="#000000">58.75</font></td>
		<td align="center" valign=middle sdval="53.2" sdnum="1033;0;0.00"><font color="#000000">53.20</font></td>
		<td align="center" valign=middle sdval="55.25" sdnum="1033;0;0.00"><font color="#000000">55.25</font></td>
		<td align="center" valign=middle sdval="45.75" sdnum="1033;0;0.00"><font color="#000000">45.75</font></td>
		<td align="center" valign=middle sdval="56" sdnum="1033;0;0.00"><font color="#000000">56.00</font></td>
		<td align="center" valign=middle sdval="48.5" sdnum="1033;0;0.00"><font color="#000000">48.50</font></td>
		<td align="center" valign=middle sdval="57.5" sdnum="1033;0;0.00"><font color="#000000">57.50</font></td>
		<td align="center" valign=middle sdval="52.6" sdnum="1033;0;0.00"><font color="#000000">52.60</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">ChatGLM3-6B</font></b></td>
		<td align="center" valign=middle sdval="56.5" sdnum="1033;0;0.00"><font color="#000000">56.50</font></td>
		<td align="center" valign=middle sdval="47.62" sdnum="1033;0;0.00"><font color="#000000">47.62</font></td>
		<td align="center" valign=middle sdval="48.38" sdnum="1033;0;0.00"><font color="#000000">48.38</font></td>
		<td align="center" valign=middle sdval="41.88" sdnum="1033;0;0.00"><font color="#000000">41.88</font></td>
		<td align="center" valign=middle sdval="54.5" sdnum="1033;0;0.00"><font color="#000000">54.50</font></td>
		<td align="center" valign=middle sdval="49.78" sdnum="1033;0;0.00"><font color="#000000">49.78</font></td>
		<td align="center" valign=middle sdval="50" sdnum="1033;0;0.00"><font color="#000000">50.00</font></td>
		<td align="center" valign=middle sdval="44.5" sdnum="1033;0;0.00"><font color="#000000">44.50</font></td>
		<td align="center" valign=middle sdval="48" sdnum="1033;0;0.00"><font color="#000000">48.00</font></td>
		<td align="center" valign=middle sdval="44.25" sdnum="1033;0;0.00"><font color="#000000">44.25</font></td>
		<td align="center" valign=middle sdval="58" sdnum="1033;0;0.00"><font color="#000000">58.00</font></td>
		<td align="center" valign=middle sdval="48.95" sdnum="1033;0;0.00"><font color="#000000">48.95</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-7B</font></b></td>
		<td align="center" valign=middle sdval="56" sdnum="1033;0;0.00"><font color="#000000">56.00</font></td>
		<td align="center" valign=middle sdval="49.62" sdnum="1033;0;0.00"><font color="#000000">49.62</font></td>
		<td align="center" valign=middle sdval="45.5" sdnum="1033;0;0.00"><font color="#000000">45.50</font></td>
		<td align="center" valign=middle sdval="40.5" sdnum="1033;0;0.00"><font color="#000000">40.50</font></td>
		<td align="center" valign=middle sdval="52.38" sdnum="1033;0;0.00"><font color="#000000">52.38</font></td>
		<td align="center" valign=middle sdval="48.8" sdnum="1033;0;0.00"><font color="#000000">48.80</font></td>
		<td align="center" valign=middle sdval="52.25" sdnum="1033;0;0.00"><font color="#000000">52.25</font></td>
		<td align="center" valign=middle sdval="43.75" sdnum="1033;0;0.00"><font color="#000000">43.75</font></td>
		<td align="center" valign=middle sdval="49" sdnum="1033;0;0.00"><font color="#000000">49.00</font></td>
		<td align="center" valign=middle sdval="47.25" sdnum="1033;0;0.00"><font color="#000000">47.25</font></td>
		<td align="center" valign=middle sdval="55" sdnum="1033;0;0.00"><font color="#000000">55.00</font></td>
		<td align="center" valign=middle sdval="49.45" sdnum="1033;0;0.00"><font color="#000000">49.45</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-3.5-1106</font></b></td>
		<td align="center" valign=middle sdval="48.75" sdnum="1033;0;0.00"><font color="#000000">48.75</font></td>
		<td align="center" valign=middle sdval="51.88" sdnum="1033;0;0.00"><font color="#000000">51.88</font></td>
		<td align="center" valign=middle sdval="51.25" sdnum="1033;0;0.00"><font color="#000000">51.25</font></td>
		<td align="center" valign=middle sdval="49.88" sdnum="1033;0;0.00"><font color="#000000">49.88</font></td>
		<td align="center" valign=middle sdval="48.38" sdnum="1033;0;0.00"><font color="#000000">48.38</font></td>
		<td align="center" valign=middle sdval="50.02" sdnum="1033;0;0.00"><font color="#000000">50.02</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="46.75" sdnum="1033;0;0.00"><font color="#000000">46.75</font></td>
		<td align="center" valign=middle sdval="41.75" sdnum="1033;0;0.00"><font color="#000000">41.75</font></td>
		<td align="center" valign=middle sdval="44.75" sdnum="1033;0;0.00"><font color="#000000">44.75</font></td>
		<td align="center" valign=middle sdval="38.75" sdnum="1033;0;0.00"><font color="#000000">38.75</font></td>
		<td align="center" valign=middle sdval="43.9" sdnum="1033;0;0.00"><font color="#000000">43.90</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-7B</font></b></td>
		<td align="center" valign=middle sdval="54.75" sdnum="1033;0;0.00"><font color="#000000">54.75</font></td>
		<td align="center" valign=middle sdval="44.38" sdnum="1033;0;0.00"><font color="#000000">44.38</font></td>
		<td align="center" valign=middle sdval="44.62" sdnum="1033;0;0.00"><font color="#000000">44.62</font></td>
		<td align="center" valign=middle sdval="42.75" sdnum="1033;0;0.00"><font color="#000000">42.75</font></td>
		<td align="center" valign=middle sdval="53" sdnum="1033;0;0.00"><font color="#000000">53.00</font></td>
		<td align="center" valign=middle sdval="47.9" sdnum="1033;0;0.00"><font color="#000000">47.90</font></td>
		<td align="center" valign=middle sdval="49" sdnum="1033;0;0.00"><font color="#000000">49.00</font></td>
		<td align="center" valign=middle sdval="42" sdnum="1033;0;0.00"><font color="#000000">42.00</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="44.75" sdnum="1033;0;0.00"><font color="#000000">44.75</font></td>
		<td align="center" valign=middle sdval="51.25" sdnum="1033;0;0.00"><font color="#000000">51.25</font></td>
		<td align="center" valign=middle sdval="46.9" sdnum="1033;0;0.00"><font color="#000000">46.90</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-3.5-0613</font></b></td>
		<td align="center" valign=middle sdval="46.62" sdnum="1033;0;0.00"><font color="#000000">46.62</font></td>
		<td align="center" valign=middle sdval="48.38" sdnum="1033;0;0.00"><font color="#000000">48.38</font></td>
		<td align="center" valign=middle sdval="51.75" sdnum="1033;0;0.00"><font color="#000000">51.75</font></td>
		<td align="center" valign=middle sdval="49.5" sdnum="1033;0;0.00"><font color="#000000">49.50</font></td>
		<td align="center" valign=middle sdval="47.38" sdnum="1033;0;0.00"><font color="#000000">47.38</font></td>
		<td align="center" valign=middle sdval="48.73" sdnum="1033;0;0.00"><font color="#000000">48.73</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="43.5" sdnum="1033;0;0.00"><font color="#000000">43.50</font></td>
		<td align="center" valign=middle sdval="39.75" sdnum="1033;0;0.00"><font color="#000000">39.75</font></td>
		<td align="center" valign=middle sdval="43.75" sdnum="1033;0;0.00"><font color="#000000">43.75</font></td>
		<td align="center" valign=middle sdval="39" sdnum="1033;0;0.00"><font color="#000000">39.00</font></td>
		<td align="center" valign=middle sdval="41.65" sdnum="1033;0;0.00"><font color="#000000">41.65</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-70B</font></b></td>
		<td align="center" valign=middle sdval="53.5" sdnum="1033;0;0.00"><font color="#000000">53.50</font></td>
		<td align="center" valign=middle sdval="43.25" sdnum="1033;0;0.00"><font color="#000000">43.25</font></td>
		<td align="center" valign=middle sdval="39.25" sdnum="1033;0;0.00"><font color="#000000">39.25</font></td>
		<td align="center" valign=middle sdval="40.25" sdnum="1033;0;0.00"><font color="#000000">40.25</font></td>
		<td align="center" valign=middle sdval="47.25" sdnum="1033;0;0.00"><font color="#000000">47.25</font></td>
		<td align="center" valign=middle sdval="44.7" sdnum="1033;0;0.00"><font color="#000000">44.70</font></td>
		<td align="center" valign=middle sdval="36" sdnum="1033;0;0.00"><font color="#000000">36.00</font></td>
		<td align="center" valign=middle sdval="38" sdnum="1033;0;0.00"><font color="#000000">38.00</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="34.75" sdnum="1033;0;0.00"><font color="#000000">34.75</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Chinese-LLaMA-2-13B</font></b></td>
		<td align="center" valign=middle sdval="45.38" sdnum="1033;0;0.00"><font color="#000000">45.38</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="39.88" sdnum="1033;0;0.00"><font color="#000000">39.88</font></td>
		<td align="center" valign=middle sdval="31.87" sdnum="1033;0;0.00"><font color="#000000">31.87</font></td>
		<td align="center" valign=middle sdval="42.12" sdnum="1033;0;0.00"><font color="#000000">42.12</font></td>
		<td align="center" valign=middle sdval="39.5" sdnum="1033;0;0.00"><font color="#000000">39.50</font></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="40.5" sdnum="1033;0;0.00"><font color="#000000">40.50</font></td>
		<td align="center" valign=middle sdval="36.3" sdnum="1033;0;0.00"><font color="#000000">36.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Chinese-LLaMA-2-7B</font></b></td>
		<td align="center" valign=middle sdval="35.62" sdnum="1033;0;0.00"><font color="#000000">35.62</font></td>
		<td align="center" valign=middle sdval="36.75" sdnum="1033;0;0.00"><font color="#000000">36.75</font></td>
		<td align="center" valign=middle sdval="35.62" sdnum="1033;0;0.00"><font color="#000000">35.62</font></td>
		<td align="center" valign=middle sdval="35.38" sdnum="1033;0;0.00"><font color="#000000">35.38</font></td>
		<td align="center" valign=middle sdval="34.38" sdnum="1033;0;0.00"><font color="#000000">34.38</font></td>
		<td align="center" valign=middle sdval="35.55" sdnum="1033;0;0.00"><font color="#000000">35.55</font></td>
		<td align="center" valign=middle sdval="34.5" sdnum="1033;0;0.00"><font color="#000000">34.50</font></td>
		<td align="center" valign=middle sdval="29" sdnum="1033;0;0.00"><font color="#000000">29.00</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="30.25" sdnum="1033;0;0.00"><font color="#000000">30.25</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="32.6" sdnum="1033;0;0.00"><font color="#000000">32.60</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Falcon-40B</font></b></td>
		<td align="center" valign=middle sdval="39.62" sdnum="1033;0;0.00"><font color="#000000">39.62</font></td>
		<td align="center" valign=middle sdval="32.25" sdnum="1033;0;0.00"><font color="#000000">32.25</font></td>
		<td align="center" valign=middle sdval="32.38" sdnum="1033;0;0.00"><font color="#000000">32.38</font></td>
		<td align="center" valign=middle sdval="30" sdnum="1033;0;0.00"><font color="#000000">30.00</font></td>
		<td align="center" valign=middle sdval="45" sdnum="1033;0;0.00"><font color="#000000">45.00</font></td>
		<td align="center" valign=middle sdval="35.85" sdnum="1033;0;0.00"><font color="#000000">35.85</font></td>
		<td align="center" valign=middle sdval="28.25" sdnum="1033;0;0.00"><font color="#000000">28.25</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="30.25" sdnum="1033;0;0.00"><font color="#000000">30.25</font></td>
		<td align="center" valign=middle sdval="29.25" sdnum="1033;0;0.00"><font color="#000000">29.25</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="31.85" sdnum="1033;0;0.00"><font color="#000000">31.85</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Mistral-7B</font></b></td>
		<td align="center" valign=middle sdval="36.12" sdnum="1033;0;0.00"><font color="#000000">36.12</font></td>
		<td align="center" valign=middle sdval="33.5" sdnum="1033;0;0.00"><font color="#000000">33.50</font></td>
		<td align="center" valign=middle sdval="32" sdnum="1033;0;0.00"><font color="#000000">32.00</font></td>
		<td align="center" valign=middle sdval="30.25" sdnum="1033;0;0.00"><font color="#000000">30.25</font></td>
		<td align="center" valign=middle sdval="35" sdnum="1033;0;0.00"><font color="#000000">35.00</font></td>
		<td align="center" valign=middle sdval="33.38" sdnum="1033;0;0.00"><font color="#000000">33.38</font></td>
		<td align="center" valign=middle sdval="32.5" sdnum="1033;0;0.00"><font color="#000000">32.50</font></td>
		<td align="center" valign=middle sdval="37.5" sdnum="1033;0;0.00"><font color="#000000">37.50</font></td>
		<td align="center" valign=middle sdval="26.25" sdnum="1033;0;0.00"><font color="#000000">26.25</font></td>
		<td align="center" valign=middle sdval="33.25" sdnum="1033;0;0.00"><font color="#000000">33.25</font></td>
		<td align="center" valign=middle sdval="31.5" sdnum="1033;0;0.00"><font color="#000000">31.50</font></td>
		<td align="center" valign=middle sdval="32.2" sdnum="1033;0;0.00"><font color="#000000">32.20</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-7B</font></b></td>
		<td align="center" valign=middle sdval="37" sdnum="1033;0;0.00"><font color="#000000">37.00</font></td>
		<td align="center" valign=middle sdval="29.88" sdnum="1033;0;0.00"><font color="#000000">29.88</font></td>
		<td align="center" valign=middle sdval="28.75" sdnum="1033;0;0.00"><font color="#000000">28.75</font></td>
		<td align="center" valign=middle sdval="34.5" sdnum="1033;0;0.00"><font color="#000000">34.50</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="33.67" sdnum="1033;0;0.00"><font color="#000000">33.67</font></td>
		<td align="center" valign=middle sdval="25.75" sdnum="1033;0;0.00"><font color="#000000">25.75</font></td>
		<td align="center" valign=middle sdval="28" sdnum="1033;0;0.00"><font color="#000000">28.00</font></td>
		<td align="center" valign=middle sdval="33.75" sdnum="1033;0;0.00"><font color="#000000">33.75</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="34.5" sdnum="1033;0;0.00"><font color="#000000">34.50</font></td>
		<td align="center" valign=middle sdval="30.35" sdnum="1033;0;0.00"><font color="#000000">30.35</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-65B</font></b></td>
		<td align="center" valign=middle sdval="32.12" sdnum="1033;0;0.00"><font color="#000000">32.12</font></td>
		<td align="center" valign=middle sdval="31.87" sdnum="1033;0;0.00"><font color="#000000">31.87</font></td>
		<td align="center" valign=middle sdval="32.75" sdnum="1033;0;0.00"><font color="#000000">32.75</font></td>
		<td align="center" valign=middle sdval="31" sdnum="1033;0;0.00"><font color="#000000">31.00</font></td>
		<td align="center" valign=middle sdval="34.88" sdnum="1033;0;0.00"><font color="#000000">34.88</font></td>
		<td align="center" valign=middle sdval="32.52" sdnum="1033;0;0.00"><font color="#000000">32.52</font></td>
		<td align="center" valign=middle sdval="30" sdnum="1033;0;0.00"><font color="#000000">30.00</font></td>
		<td align="center" valign=middle sdval="32.25" sdnum="1033;0;0.00"><font color="#000000">32.25</font></td>
		<td align="center" valign=middle sdval="29" sdnum="1033;0;0.00"><font color="#000000">29.00</font></td>
		<td align="center" valign=middle sdval="35.5" sdnum="1033;0;0.00"><font color="#000000">35.50</font></td>
		<td align="center" valign=middle sdval="29" sdnum="1033;0;0.00"><font color="#000000">29.00</font></td>
		<td align="center" valign=middle sdval="31.15" sdnum="1033;0;0.00"><font color="#000000">31.15</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-13B</font></b></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="31.87" sdnum="1033;0;0.00"><font color="#000000">31.87</font></td>
		<td align="center" valign=middle sdval="31.75" sdnum="1033;0;0.00"><font color="#000000">31.75</font></td>
		<td align="center" valign=middle sdval="33.42" sdnum="1033;0;0.00"><font color="#000000">33.42</font></td>
		<td align="center" valign=middle sdval="28.75" sdnum="1033;0;0.00"><font color="#000000">28.75</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="25.25" sdnum="1033;0;0.00"><font color="#000000">25.25</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="28.25" sdnum="1033;0;0.00"><font color="#000000">28.25</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-30B</font></b></td>
		<td align="center" valign=middle sdval="24.88" sdnum="1033;0;0.00"><font color="#000000">24.88</font></td>
		<td align="center" valign=middle sdval="31.13" sdnum="1033;0;0.00"><font color="#000000">31.13</font></td>
		<td align="center" valign=middle sdval="30.25" sdnum="1033;0;0.00"><font color="#000000">30.25</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="28.62" sdnum="1033;0;0.00"><font color="#000000">28.62</font></td>
		<td align="center" valign=middle sdval="28.52" sdnum="1033;0;0.00"><font color="#000000">28.52</font></td>
		<td align="center" valign=middle sdval="30" sdnum="1033;0;0.00"><font color="#000000">30.00</font></td>
		<td align="center" valign=middle sdval="28.75" sdnum="1033;0;0.00"><font color="#000000">28.75</font></td>
		<td align="center" valign=middle sdval="26" sdnum="1033;0;0.00"><font color="#000000">26.00</font></td>
		<td align="center" valign=middle sdval="31.75" sdnum="1033;0;0.00"><font color="#000000">31.75</font></td>
		<td align="center" valign=middle sdval="28" sdnum="1033;0;0.00"><font color="#000000">28.00</font></td>
		<td align="center" valign=middle sdval="28.9" sdnum="1033;0;0.00"><font color="#000000">28.90</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-13B</font></b></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="28.25" sdnum="1033;0;0.00"><font color="#000000">28.25</font></td>
		<td align="center" valign=middle sdval="26.5" sdnum="1033;0;0.00"><font color="#000000">26.50</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="27.9" sdnum="1033;0;0.00"><font color="#000000">27.90</font></td>
		<td align="center" valign=middle sdval="27.25" sdnum="1033;0;0.00"><font color="#000000">27.25</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="27.25" sdnum="1033;0;0.00"><font color="#000000">27.25</font></td>
		<td align="center" valign=middle sdval="26" sdnum="1033;0;0.00"><font color="#000000">26.00</font></td>
		<td align="center" valign=middle sdval="29" sdnum="1033;0;0.00"><font color="#000000">29.00</font></td>
		<td align="center" valign=middle sdval="27.85" sdnum="1033;0;0.00"><font color="#000000">27.85</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Falcon-7B</font></b></td>
		<td align="center" valign=middle sdval="23.88" sdnum="1033;0;0.00"><font color="#000000">23.88</font></td>
		<td align="center" valign=middle sdval="28.12" sdnum="1033;0;0.00"><font color="#000000">28.12</font></td>
		<td align="center" valign=middle sdval="24.5" sdnum="1033;0;0.00"><font color="#000000">24.50</font></td>
		<td align="center" valign=middle sdval="28" sdnum="1033;0;0.00"><font color="#000000">28.00</font></td>
		<td align="center" valign=middle sdval="28.12" sdnum="1033;0;0.00"><font color="#000000">28.12</font></td>
		<td align="center" valign=middle sdval="26.52" sdnum="1033;0;0.00"><font color="#000000">26.52</font></td>
		<td align="center" valign=middle sdval="24.75" sdnum="1033;0;0.00"><font color="#000000">24.75</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="31.5" sdnum="1033;0;0.00"><font color="#000000">31.50</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="25.25" sdnum="1033;0;0.00"><font color="#000000">25.25</font></td>
		<td align="center" valign=middle sdval="28.35" sdnum="1033;0;0.00"><font color="#000000">28.35</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-7B</font></b></td>
		<td align="center" valign=middle sdval="25.5" sdnum="1033;0;0.00"><font color="#000000">25.50</font></td>
		<td align="center" valign=middle sdval="31.87" sdnum="1033;0;0.00"><font color="#000000">31.87</font></td>
		<td align="center" valign=middle sdval="25.87" sdnum="1033;0;0.00"><font color="#000000">25.87</font></td>
		<td align="center" valign=middle sdval="26" sdnum="1033;0;0.00"><font color="#000000">26.00</font></td>
		<td align="center" valign=middle sdval="28.88" sdnum="1033;0;0.00"><font color="#000000">28.88</font></td>
		<td align="center" valign=middle sdval="27.62" sdnum="1033;0;0.00"><font color="#000000">27.62</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="24.75" sdnum="1033;0;0.00"><font color="#000000">24.75</font></td>
		<td align="center" valign=middle sdval="20.5" sdnum="1033;0;0.00"><font color="#000000">20.50</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="29" sdnum="1033;0;0.00"><font color="#000000">29.00</font></td>
		<td align="center" valign=middle sdval="26.1" sdnum="1033;0;0.00"><font color="#000000">26.10</font></td>
	</tr>
</table>

### RoleEval (en)

<table cellspacing="0" border="0">
	<colgroup width="211"></colgroup>
	<colgroup span="2" width="50"></colgroup>
	<colgroup width="51"></colgroup>
	<colgroup span="5" width="50"></colgroup>
	<colgroup width="51"></colgroup>
	<colgroup span="2" width="50"></colgroup>
	<colgroup width="54"></colgroup>
	<tr>
		<td rowspan=2 height="43" align="center" valign=middle><b><font color="#000000">Model</font></b></td>
		<td colspan=6 align="center" valign=middle><b><font color="#000000">RoleEval-Global (4,000 questions)</font></b></td>
		<td colspan=6 align="center" valign=middle><b><font color="#000000">RoleEval-Chinese (2,000 questions)</font></b></td>
		</tr>
	<tr>
		<td align="center" valign=middle><b><font color="#000000">Celebrities</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Anime and Comics</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Movies and TV Series</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Games</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Fiction</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Avg.</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Celebrities</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Anime and Comics</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Movies and TV Series</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Games</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Fiction</font></b></td>
		<td align="center" valign=middle><b><font color="#000000">Avg.</font></b></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-4-0613</font></b></td>
		<td align="center" valign=middle sdval="77.62" sdnum="1033;0;0.00"><b><font color="#000000">77.62</font></b></td>
		<td align="center" valign=middle sdval="79.5" sdnum="1033;0;0.00"><b><font color="#000000">79.50</font></b></td>
		<td align="center" valign=middle sdval="73.12" sdnum="1033;0;0.00"><font color="#000000">73.12</font></td>
		<td align="center" valign=middle sdval="74.88" sdnum="1033;0;0.00"><font color="#000000">74.88</font></td>
		<td align="center" valign=middle sdval="75" sdnum="1033;0;0.00"><b><font color="#000000">75.00</font></b></td>
		<td align="center" valign=middle sdval="76.02" sdnum="1033;0;0.00"><b><font color="#000000">76.02</font></b></td>
		<td align="center" valign=middle sdval="54.25" sdnum="1033;0;0.00"><font color="#000000">54.25</font></td>
		<td align="center" valign=middle sdval="61.75" sdnum="1033;0;0.00"><font color="#000000">61.75</font></td>
		<td align="center" valign=middle sdval="63" sdnum="1033;0;0.00"><b><font color="#000000">63.00</font></b></td>
		<td align="center" valign=middle sdval="63" sdnum="1033;0;0.00"><b><font color="#000000">63.00</font></b></td>
		<td align="center" valign=middle sdval="63" sdnum="1033;0;0.00"><b><font color="#000000">63.00</font></b></td>
		<td align="center" valign=middle sdval="61" sdnum="1033;0;0.00"><b><font color="#000000">61.00</font></b></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-4-1106</font></b></td>
		<td align="center" valign=middle sdval="75.12" sdnum="1033;0;0.00"><font color="#000000">75.12</font></td>
		<td align="center" valign=middle sdval="78.75" sdnum="1033;0;0.00"><font color="#000000">78.75</font></td>
		<td align="center" valign=middle sdval="75" sdnum="1033;0;0.00"><b><font color="#000000">75.00</font></b></td>
		<td align="center" valign=middle sdval="76.12" sdnum="1033;0;0.00"><b><font color="#000000">76.12</font></b></td>
		<td align="center" valign=middle sdval="75" sdnum="1033;0;0.00"><b><font color="#000000">75.00</font></b></td>
		<td align="center" valign=middle sdval="76" sdnum="1033;0;0.00"><font color="#000000">76.00</font></td>
		<td align="center" valign=middle sdval="57.5" sdnum="1033;0;0.00"><b><font color="#000000">57.50</font></b></td>
		<td align="center" valign=middle sdval="63.5" sdnum="1033;0;0.00"><b><font color="#000000">63.50</font></b></td>
		<td align="center" valign=middle sdval="60" sdnum="1033;0;0.00"><font color="#000000">60.00</font></td>
		<td align="center" valign=middle sdval="62.5" sdnum="1033;0;0.00"><font color="#000000">62.50</font></td>
		<td align="center" valign=middle sdval="58" sdnum="1033;0;0.00"><font color="#000000">58.00</font></td>
		<td align="center" valign=middle sdval="60.3" sdnum="1033;0;0.00"><font color="#000000">60.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Yi-34B</font></b></td>
		<td align="center" valign=middle sdval="73.12" sdnum="1033;0;0.00"><font color="#000000">73.12</font></td>
		<td align="center" valign=middle sdval="61.75" sdnum="1033;0;0.00"><font color="#000000">61.75</font></td>
		<td align="center" valign=middle sdval="67.88" sdnum="1033;0;0.00"><font color="#000000">67.88</font></td>
		<td align="center" valign=middle sdval="57.12" sdnum="1033;0;0.00"><font color="#000000">57.12</font></td>
		<td align="center" valign=middle sdval="67.25" sdnum="1033;0;0.00"><font color="#000000">67.25</font></td>
		<td align="center" valign=middle sdval="65.42" sdnum="1033;0;0.00"><font color="#000000">65.42</font></td>
		<td align="center" valign=middle sdval="56" sdnum="1033;0;0.00"><font color="#000000">56.00</font></td>
		<td align="center" valign=middle sdval="52" sdnum="1033;0;0.00"><font color="#000000">52.00</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="55" sdnum="1033;0;0.00"><font color="#000000">55.00</font></td>
		<td align="center" valign=middle sdval="57" sdnum="1033;0;0.00"><font color="#000000">57.00</font></td>
		<td align="center" valign=middle sdval="53.5" sdnum="1033;0;0.00"><font color="#000000">53.50</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-72B</font></b></td>
		<td align="center" valign=middle sdval="70.12" sdnum="1033;0;0.00"><font color="#000000">70.12</font></td>
		<td align="center" valign=middle sdval="62" sdnum="1033;0;0.00"><font color="#000000">62.00</font></td>
		<td align="center" valign=middle sdval="69" sdnum="1033;0;0.00"><font color="#000000">69.00</font></td>
		<td align="center" valign=middle sdval="55.75" sdnum="1033;0;0.00"><font color="#000000">55.75</font></td>
		<td align="center" valign=middle sdval="69.5" sdnum="1033;0;0.00"><font color="#000000">69.50</font></td>
		<td align="center" valign=middle sdval="65.27" sdnum="1033;0;0.00"><font color="#000000">65.27</font></td>
		<td align="center" valign=middle sdval="52.75" sdnum="1033;0;0.00"><font color="#000000">52.75</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="46.5" sdnum="1033;0;0.00"><font color="#000000">46.50</font></td>
		<td align="center" valign=middle sdval="54.25" sdnum="1033;0;0.00"><font color="#000000">54.25</font></td>
		<td align="center" valign=middle sdval="50.5" sdnum="1033;0;0.00"><font color="#000000">50.50</font></td>
		<td align="center" valign=middle sdval="50.3" sdnum="1033;0;0.00"><font color="#000000">50.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-3.5-0613</font></b></td>
		<td align="center" valign=middle sdval="57.38" sdnum="1033;0;0.00"><font color="#000000">57.38</font></td>
		<td align="center" valign=middle sdval="59.62" sdnum="1033;0;0.00"><font color="#000000">59.62</font></td>
		<td align="center" valign=middle sdval="58.13" sdnum="1033;0;0.00"><font color="#000000">58.13</font></td>
		<td align="center" valign=middle sdval="59.5" sdnum="1033;0;0.00"><font color="#000000">59.50</font></td>
		<td align="center" valign=middle sdval="57.5" sdnum="1033;0;0.00"><font color="#000000">57.50</font></td>
		<td align="center" valign=middle sdval="58.43" sdnum="1033;0;0.00"><font color="#000000">58.43</font></td>
		<td align="center" valign=middle sdval="42" sdnum="1033;0;0.00"><font color="#000000">42.00</font></td>
		<td align="center" valign=middle sdval="47.75" sdnum="1033;0;0.00"><font color="#000000">47.75</font></td>
		<td align="center" valign=middle sdval="42.5" sdnum="1033;0;0.00"><font color="#000000">42.50</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="45.5" sdnum="1033;0;0.00"><font color="#000000">45.50</font></td>
		<td align="center" valign=middle sdval="44" sdnum="1033;0;0.00"><font color="#000000">44.00</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-70B</font></b></td>
		<td align="center" valign=middle sdval="63.25" sdnum="1033;0;0.00"><font color="#000000">63.25</font></td>
		<td align="center" valign=middle sdval="57.38" sdnum="1033;0;0.00"><font color="#000000">57.38</font></td>
		<td align="center" valign=middle sdval="59" sdnum="1033;0;0.00"><font color="#000000">59.00</font></td>
		<td align="center" valign=middle sdval="50" sdnum="1033;0;0.00"><font color="#000000">50.00</font></td>
		<td align="center" valign=middle sdval="63.25" sdnum="1033;0;0.00"><font color="#000000">63.25</font></td>
		<td align="center" valign=middle sdval="58.58" sdnum="1033;0;0.00"><font color="#000000">58.58</font></td>
		<td align="center" valign=middle sdval="43.25" sdnum="1033;0;0.00"><font color="#000000">43.25</font></td>
		<td align="center" valign=middle sdval="41.5" sdnum="1033;0;0.00"><font color="#000000">41.50</font></td>
		<td align="center" valign=middle sdval="40.25" sdnum="1033;0;0.00"><font color="#000000">40.25</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="43.5" sdnum="1033;0;0.00"><font color="#000000">43.50</font></td>
		<td align="center" valign=middle sdval="43.2" sdnum="1033;0;0.00"><font color="#000000">43.20</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">GPT-3.5-1106</font></b></td>
		<td align="center" valign=middle sdval="58.75" sdnum="1033;0;0.00"><font color="#000000">58.75</font></td>
		<td align="center" valign=middle sdval="56.62" sdnum="1033;0;0.00"><font color="#000000">56.62</font></td>
		<td align="center" valign=middle sdval="55.75" sdnum="1033;0;0.00"><font color="#000000">55.75</font></td>
		<td align="center" valign=middle sdval="58" sdnum="1033;0;0.00"><font color="#000000">58.00</font></td>
		<td align="center" valign=middle sdval="55" sdnum="1033;0;0.00"><font color="#000000">55.00</font></td>
		<td align="center" valign=middle sdval="56.82" sdnum="1033;0;0.00"><font color="#000000">56.82</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="45.5" sdnum="1033;0;0.00"><font color="#000000">45.50</font></td>
		<td align="center" valign=middle sdval="44" sdnum="1033;0;0.00"><font color="#000000">44.00</font></td>
		<td align="center" valign=middle sdval="44.5" sdnum="1033;0;0.00"><font color="#000000">44.50</font></td>
		<td align="center" valign=middle sdval="46" sdnum="1033;0;0.00"><font color="#000000">46.00</font></td>
		<td align="center" valign=middle sdval="43.65" sdnum="1033;0;0.00"><font color="#000000">43.65</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Yi-6B</font></b></td>
		<td align="center" valign=middle sdval="59.25" sdnum="1033;0;0.00"><font color="#000000">59.25</font></td>
		<td align="center" valign=middle sdval="52" sdnum="1033;0;0.00"><font color="#000000">52.00</font></td>
		<td align="center" valign=middle sdval="54.12" sdnum="1033;0;0.00"><font color="#000000">54.12</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="56.25" sdnum="1033;0;0.00"><font color="#000000">56.25</font></td>
		<td align="center" valign=middle sdval="53.82" sdnum="1033;0;0.00"><font color="#000000">53.82</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="41.5" sdnum="1033;0;0.00"><font color="#000000">41.50</font></td>
		<td align="center" valign=middle sdval="44.25" sdnum="1033;0;0.00"><font color="#000000">44.25</font></td>
		<td align="center" valign=middle sdval="45" sdnum="1033;0;0.00"><font color="#000000">45.00</font></td>
		<td align="center" valign=middle sdval="42.3" sdnum="1033;0;0.00"><font color="#000000">42.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-14B</font></b></td>
		<td align="center" valign=middle sdval="61.12" sdnum="1033;0;0.00"><font color="#000000">61.12</font></td>
		<td align="center" valign=middle sdval="49" sdnum="1033;0;0.00"><font color="#000000">49.00</font></td>
		<td align="center" valign=middle sdval="53.87" sdnum="1033;0;0.00"><font color="#000000">53.87</font></td>
		<td align="center" valign=middle sdval="45.38" sdnum="1033;0;0.00"><font color="#000000">45.38</font></td>
		<td align="center" valign=middle sdval="56.12" sdnum="1033;0;0.00"><font color="#000000">56.12</font></td>
		<td align="center" valign=middle sdval="53.1" sdnum="1033;0;0.00"><font color="#000000">53.10</font></td>
		<td align="center" valign=middle sdval="41" sdnum="1033;0;0.00"><font color="#000000">41.00</font></td>
		<td align="center" valign=middle sdval="38.75" sdnum="1033;0;0.00"><font color="#000000">38.75</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="43.25" sdnum="1033;0;0.00"><font color="#000000">43.25</font></td>
		<td align="center" valign=middle sdval="41" sdnum="1033;0;0.00"><font color="#000000">41.00</font></td>
		<td align="center" valign=middle sdval="40.45" sdnum="1033;0;0.00"><font color="#000000">40.45</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">MiniMax</font></b></td>
		<td align="center" valign=middle sdval="54.87" sdnum="1033;0;0.00"><font color="#000000">54.87</font></td>
		<td align="center" valign=middle sdval="56.38" sdnum="1033;0;0.00"><font color="#000000">56.38</font></td>
		<td align="center" valign=middle sdval="53.5" sdnum="1033;0;0.00"><font color="#000000">53.50</font></td>
		<td align="center" valign=middle sdval="54.12" sdnum="1033;0;0.00"><font color="#000000">54.12</font></td>
		<td align="center" valign=middle sdval="51.38" sdnum="1033;0;0.00"><font color="#000000">51.38</font></td>
		<td align="center" valign=middle sdval="54.05" sdnum="1033;0;0.00"><font color="#000000">54.05</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="39.5" sdnum="1033;0;0.00"><font color="#000000">39.50</font></td>
		<td align="center" valign=middle sdval="40.75" sdnum="1033;0;0.00"><font color="#000000">40.75</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="39" sdnum="1033;0;0.00"><font color="#000000">39.00</font></td>
		<td align="center" valign=middle sdval="38.3" sdnum="1033;0;0.00"><font color="#000000">38.30</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-65B</font></b></td>
		<td align="center" valign=middle sdval="58.13" sdnum="1033;0;0.00"><font color="#000000">58.13</font></td>
		<td align="center" valign=middle sdval="50.5" sdnum="1033;0;0.00"><font color="#000000">50.50</font></td>
		<td align="center" valign=middle sdval="54.37" sdnum="1033;0;0.00"><font color="#000000">54.37</font></td>
		<td align="center" valign=middle sdval="47.62" sdnum="1033;0;0.00"><font color="#000000">47.62</font></td>
		<td align="center" valign=middle sdval="54.5" sdnum="1033;0;0.00"><font color="#000000">54.50</font></td>
		<td align="center" valign=middle sdval="53.02" sdnum="1033;0;0.00"><font color="#000000">53.02</font></td>
		<td align="center" valign=middle sdval="41.5" sdnum="1033;0;0.00"><font color="#000000">41.50</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="33.5" sdnum="1033;0;0.00"><font color="#000000">33.50</font></td>
		<td align="center" valign=middle sdval="43.25" sdnum="1033;0;0.00"><font color="#000000">43.25</font></td>
		<td align="center" valign=middle sdval="37.5" sdnum="1033;0;0.00"><font color="#000000">37.50</font></td>
		<td align="center" valign=middle sdval="38.85" sdnum="1033;0;0.00"><font color="#000000">38.85</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Skywork-13B</font></b></td>
		<td align="center" valign=middle sdval="56.25" sdnum="1033;0;0.00"><font color="#000000">56.25</font></td>
		<td align="center" valign=middle sdval="46.75" sdnum="1033;0;0.00"><font color="#000000">46.75</font></td>
		<td align="center" valign=middle sdval="51.62" sdnum="1033;0;0.00"><font color="#000000">51.62</font></td>
		<td align="center" valign=middle sdval="44.38" sdnum="1033;0;0.00"><font color="#000000">44.38</font></td>
		<td align="center" valign=middle sdval="53.62" sdnum="1033;0;0.00"><font color="#000000">53.62</font></td>
		<td align="center" valign=middle sdval="50.52" sdnum="1033;0;0.00"><font color="#000000">50.52</font></td>
		<td align="center" valign=middle sdval="39.25" sdnum="1033;0;0.00"><font color="#000000">39.25</font></td>
		<td align="center" valign=middle sdval="34.5" sdnum="1033;0;0.00"><font color="#000000">34.50</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="41.75" sdnum="1033;0;0.00"><font color="#000000">41.75</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="38.45" sdnum="1033;0;0.00"><font color="#000000">38.45</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-13B</font></b></td>
		<td align="center" valign=middle sdval="56.12" sdnum="1033;0;0.00"><font color="#000000">56.12</font></td>
		<td align="center" valign=middle sdval="47.5" sdnum="1033;0;0.00"><font color="#000000">47.50</font></td>
		<td align="center" valign=middle sdval="51.5" sdnum="1033;0;0.00"><font color="#000000">51.50</font></td>
		<td align="center" valign=middle sdval="45.62" sdnum="1033;0;0.00"><font color="#000000">45.62</font></td>
		<td align="center" valign=middle sdval="54" sdnum="1033;0;0.00"><font color="#000000">54.00</font></td>
		<td align="center" valign=middle sdval="50.95" sdnum="1033;0;0.00"><font color="#000000">50.95</font></td>
		<td align="center" valign=middle sdval="35.5" sdnum="1033;0;0.00"><font color="#000000">35.50</font></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="31.25" sdnum="1033;0;0.00"><font color="#000000">31.25</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="34.75" sdnum="1033;0;0.00"><font color="#000000">34.75</font></td>
		<td align="center" valign=middle sdval="36.05" sdnum="1033;0;0.00"><font color="#000000">36.05</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">ChatGLM3-6B</font></b></td>
		<td align="center" valign=middle sdval="55.12" sdnum="1033;0;0.00"><font color="#000000">55.12</font></td>
		<td align="center" valign=middle sdval="46.62" sdnum="1033;0;0.00"><font color="#000000">46.62</font></td>
		<td align="center" valign=middle sdval="49.25" sdnum="1033;0;0.00"><font color="#000000">49.25</font></td>
		<td align="center" valign=middle sdval="43.25" sdnum="1033;0;0.00"><font color="#000000">43.25</font></td>
		<td align="center" valign=middle sdval="52.62" sdnum="1033;0;0.00"><font color="#000000">52.62</font></td>
		<td align="center" valign=middle sdval="49.37" sdnum="1033;0;0.00"><font color="#000000">49.37</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="35.25" sdnum="1033;0;0.00"><font color="#000000">35.25</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="43.5" sdnum="1033;0;0.00"><font color="#000000">43.50</font></td>
		<td align="center" valign=middle sdval="38.7" sdnum="1033;0;0.00"><font color="#000000">38.70</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Mistral-7B</font></b></td>
		<td align="center" valign=middle sdval="54.87" sdnum="1033;0;0.00"><font color="#000000">54.87</font></td>
		<td align="center" valign=middle sdval="46.75" sdnum="1033;0;0.00"><font color="#000000">46.75</font></td>
		<td align="center" valign=middle sdval="49.62" sdnum="1033;0;0.00"><font color="#000000">49.62</font></td>
		<td align="center" valign=middle sdval="44.25" sdnum="1033;0;0.00"><font color="#000000">44.25</font></td>
		<td align="center" valign=middle sdval="52.25" sdnum="1033;0;0.00"><font color="#000000">52.25</font></td>
		<td align="center" valign=middle sdval="49.55" sdnum="1033;0;0.00"><font color="#000000">49.55</font></td>
		<td align="center" valign=middle sdval="35.75" sdnum="1033;0;0.00"><font color="#000000">35.75</font></td>
		<td align="center" valign=middle sdval="42" sdnum="1033;0;0.00"><font color="#000000">42.00</font></td>
		<td align="center" valign=middle sdval="30" sdnum="1033;0;0.00"><font color="#000000">30.00</font></td>
		<td align="center" valign=middle sdval="41.75" sdnum="1033;0;0.00"><font color="#000000">41.75</font></td>
		<td align="center" valign=middle sdval="31.5" sdnum="1033;0;0.00"><font color="#000000">31.50</font></td>
		<td align="center" valign=middle sdval="36.2" sdnum="1033;0;0.00"><font color="#000000">36.20</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Qwen-7B</font></b></td>
		<td align="center" valign=middle sdval="53.87" sdnum="1033;0;0.00"><font color="#000000">53.87</font></td>
		<td align="center" valign=middle sdval="46.12" sdnum="1033;0;0.00"><font color="#000000">46.12</font></td>
		<td align="center" valign=middle sdval="48.12" sdnum="1033;0;0.00"><font color="#000000">48.12</font></td>
		<td align="center" valign=middle sdval="40" sdnum="1033;0;0.00"><font color="#000000">40.00</font></td>
		<td align="center" valign=middle sdval="51.12" sdnum="1033;0;0.00"><font color="#000000">51.12</font></td>
		<td align="center" valign=middle sdval="47.85" sdnum="1033;0;0.00"><font color="#000000">47.85</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="36" sdnum="1033;0;0.00"><font color="#000000">36.00</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="42.25" sdnum="1033;0;0.00"><font color="#000000">42.25</font></td>
		<td align="center" valign=middle sdval="40" sdnum="1033;0;0.00"><font color="#000000">40.00</font></td>
		<td align="center" valign=middle sdval="38.15" sdnum="1033;0;0.00"><font color="#000000">38.15</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-30B</font></b></td>
		<td align="center" valign=middle sdval="51.62" sdnum="1033;0;0.00"><font color="#000000">51.62</font></td>
		<td align="center" valign=middle sdval="46.88" sdnum="1033;0;0.00"><font color="#000000">46.88</font></td>
		<td align="center" valign=middle sdval="48.62" sdnum="1033;0;0.00"><font color="#000000">48.62</font></td>
		<td align="center" valign=middle sdval="43.12" sdnum="1033;0;0.00"><font color="#000000">43.12</font></td>
		<td align="center" valign=middle sdval="52.62" sdnum="1033;0;0.00"><font color="#000000">52.62</font></td>
		<td align="center" valign=middle sdval="48.57" sdnum="1033;0;0.00"><font color="#000000">48.57</font></td>
		<td align="center" valign=middle sdval="34.75" sdnum="1033;0;0.00"><font color="#000000">34.75</font></td>
		<td align="center" valign=middle sdval="35.75" sdnum="1033;0;0.00"><font color="#000000">35.75</font></td>
		<td align="center" valign=middle sdval="30.75" sdnum="1033;0;0.00"><font color="#000000">30.75</font></td>
		<td align="center" valign=middle sdval="40" sdnum="1033;0;0.00"><font color="#000000">40.00</font></td>
		<td align="center" valign=middle sdval="35" sdnum="1033;0;0.00"><font color="#000000">35.00</font></td>
		<td align="center" valign=middle sdval="35.25" sdnum="1033;0;0.00"><font color="#000000">35.25</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Baichuan2-7B</font></b></td>
		<td align="center" valign=middle sdval="51" sdnum="1033;0;0.00"><font color="#000000">51.00</font></td>
		<td align="center" valign=middle sdval="45.12" sdnum="1033;0;0.00"><font color="#000000">45.12</font></td>
		<td align="center" valign=middle sdval="49" sdnum="1033;0;0.00"><font color="#000000">49.00</font></td>
		<td align="center" valign=middle sdval="42.12" sdnum="1033;0;0.00"><font color="#000000">42.12</font></td>
		<td align="center" valign=middle sdval="50" sdnum="1033;0;0.00"><font color="#000000">50.00</font></td>
		<td align="center" valign=middle sdval="47.45" sdnum="1033;0;0.00"><font color="#000000">47.45</font></td>
		<td align="center" valign=middle sdval="37.25" sdnum="1033;0;0.00"><font color="#000000">37.25</font></td>
		<td align="center" valign=middle sdval="35.75" sdnum="1033;0;0.00"><font color="#000000">35.75</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="40.25" sdnum="1033;0;0.00"><font color="#000000">40.25</font></td>
		<td align="center" valign=middle sdval="37" sdnum="1033;0;0.00"><font color="#000000">37.00</font></td>
		<td align="center" valign=middle sdval="36.65" sdnum="1033;0;0.00"><font color="#000000">36.65</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Falcon-40B</font></b></td>
		<td align="center" valign=middle sdval="47.38" sdnum="1033;0;0.00"><font color="#000000">47.38</font></td>
		<td align="center" valign=middle sdval="45" sdnum="1033;0;0.00"><font color="#000000">45.00</font></td>
		<td align="center" valign=middle sdval="49.62" sdnum="1033;0;0.00"><font color="#000000">49.62</font></td>
		<td align="center" valign=middle sdval="43.12" sdnum="1033;0;0.00"><font color="#000000">43.12</font></td>
		<td align="center" valign=middle sdval="50" sdnum="1033;0;0.00"><font color="#000000">50.00</font></td>
		<td align="center" valign=middle sdval="47.02" sdnum="1033;0;0.00"><font color="#000000">47.02</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="38.25" sdnum="1033;0;0.00"><font color="#000000">38.25</font></td>
		<td align="center" valign=middle sdval="30.75" sdnum="1033;0;0.00"><font color="#000000">30.75</font></td>
		<td align="center" valign=middle sdval="38.75" sdnum="1033;0;0.00"><font color="#000000">38.75</font></td>
		<td align="center" valign=middle sdval="35.25" sdnum="1033;0;0.00"><font color="#000000">35.25</font></td>
		<td align="center" valign=middle sdval="35.4" sdnum="1033;0;0.00"><font color="#000000">35.40</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Chinese-LLaMA-2-13B</font></b></td>
		<td align="center" valign=middle sdval="47.75" sdnum="1033;0;0.00"><font color="#000000">47.75</font></td>
		<td align="center" valign=middle sdval="46" sdnum="1033;0;0.00"><font color="#000000">46.00</font></td>
		<td align="center" valign=middle sdval="46.88" sdnum="1033;0;0.00"><font color="#000000">46.88</font></td>
		<td align="center" valign=middle sdval="45" sdnum="1033;0;0.00"><font color="#000000">45.00</font></td>
		<td align="center" valign=middle sdval="48.38" sdnum="1033;0;0.00"><font color="#000000">48.38</font></td>
		<td align="center" valign=middle sdval="46.8" sdnum="1033;0;0.00"><font color="#000000">46.80</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="37.5" sdnum="1033;0;0.00"><font color="#000000">37.50</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
		<td align="center" valign=middle sdval="34.35" sdnum="1033;0;0.00"><font color="#000000">34.35</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-13B</font></b></td>
		<td align="center" valign=middle sdval="49.38" sdnum="1033;0;0.00"><font color="#000000">49.38</font></td>
		<td align="center" valign=middle sdval="43.5" sdnum="1033;0;0.00"><font color="#000000">43.50</font></td>
		<td align="center" valign=middle sdval="46.5" sdnum="1033;0;0.00"><font color="#000000">46.50</font></td>
		<td align="center" valign=middle sdval="44.25" sdnum="1033;0;0.00"><font color="#000000">44.25</font></td>
		<td align="center" valign=middle sdval="48.25" sdnum="1033;0;0.00"><font color="#000000">48.25</font></td>
		<td align="center" valign=middle sdval="46.38" sdnum="1033;0;0.00"><font color="#000000">46.38</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="33.25" sdnum="1033;0;0.00"><font color="#000000">33.25</font></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="33.25" sdnum="1033;0;0.00"><font color="#000000">33.25</font></td>
		<td align="center" valign=middle sdval="34" sdnum="1033;0;0.00"><font color="#000000">34.00</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-13B</font></b></td>
		<td align="center" valign=middle sdval="39.38" sdnum="1033;0;0.00"><font color="#000000">39.38</font></td>
		<td align="center" valign=middle sdval="40.25" sdnum="1033;0;0.00"><font color="#000000">40.25</font></td>
		<td align="center" valign=middle sdval="39.88" sdnum="1033;0;0.00"><font color="#000000">39.88</font></td>
		<td align="center" valign=middle sdval="40.62" sdnum="1033;0;0.00"><font color="#000000">40.62</font></td>
		<td align="center" valign=middle sdval="43" sdnum="1033;0;0.00"><font color="#000000">43.00</font></td>
		<td align="center" valign=middle sdval="40.63" sdnum="1033;0;0.00"><font color="#000000">40.63</font></td>
		<td align="center" valign=middle sdval="32.75" sdnum="1033;0;0.00"><font color="#000000">32.75</font></td>
		<td align="center" valign=middle sdval="31.75" sdnum="1033;0;0.00"><font color="#000000">31.75</font></td>
		<td align="center" valign=middle sdval="30.75" sdnum="1033;0;0.00"><font color="#000000">30.75</font></td>
		<td align="center" valign=middle sdval="38.5" sdnum="1033;0;0.00"><font color="#000000">38.50</font></td>
		<td align="center" valign=middle sdval="32" sdnum="1033;0;0.00"><font color="#000000">32.00</font></td>
		<td align="center" valign=middle sdval="33.15" sdnum="1033;0;0.00"><font color="#000000">33.15</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-2-7B</font></b></td>
		<td align="center" valign=middle sdval="38.88" sdnum="1033;0;0.00"><font color="#000000">38.88</font></td>
		<td align="center" valign=middle sdval="37" sdnum="1033;0;0.00"><font color="#000000">37.00</font></td>
		<td align="center" valign=middle sdval="37.5" sdnum="1033;0;0.00"><font color="#000000">37.50</font></td>
		<td align="center" valign=middle sdval="41.62" sdnum="1033;0;0.00"><font color="#000000">41.62</font></td>
		<td align="center" valign=middle sdval="42.38" sdnum="1033;0;0.00"><font color="#000000">42.38</font></td>
		<td align="center" valign=middle sdval="39.48" sdnum="1033;0;0.00"><font color="#000000">39.48</font></td>
		<td align="center" valign=middle sdval="28.75" sdnum="1033;0;0.00"><font color="#000000">28.75</font></td>
		<td align="center" valign=middle sdval="29.25" sdnum="1033;0;0.00"><font color="#000000">29.25</font></td>
		<td align="center" valign=middle sdval="32.75" sdnum="1033;0;0.00"><font color="#000000">32.75</font></td>
		<td align="center" valign=middle sdval="37.5" sdnum="1033;0;0.00"><font color="#000000">37.50</font></td>
		<td align="center" valign=middle sdval="32.25" sdnum="1033;0;0.00"><font color="#000000">32.25</font></td>
		<td align="center" valign=middle sdval="32.1" sdnum="1033;0;0.00"><font color="#000000">32.10</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Chinese-LLaMA-2-7B</font></b></td>
		<td align="center" valign=middle sdval="36.5" sdnum="1033;0;0.00"><font color="#000000">36.50</font></td>
		<td align="center" valign=middle sdval="30.75" sdnum="1033;0;0.00"><font color="#000000">30.75</font></td>
		<td align="center" valign=middle sdval="31.75" sdnum="1033;0;0.00"><font color="#000000">31.75</font></td>
		<td align="center" valign=middle sdval="36.25" sdnum="1033;0;0.00"><font color="#000000">36.25</font></td>
		<td align="center" valign=middle sdval="39.5" sdnum="1033;0;0.00"><font color="#000000">39.50</font></td>
		<td align="center" valign=middle sdval="34.95" sdnum="1033;0;0.00"><font color="#000000">34.95</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="29.9" sdnum="1033;0;0.00"><font color="#000000">29.90</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">LLaMA-7B</font></b></td>
		<td align="center" valign=middle sdval="29.38" sdnum="1033;0;0.00"><font color="#000000">29.38</font></td>
		<td align="center" valign=middle sdval="30.5" sdnum="1033;0;0.00"><font color="#000000">30.50</font></td>
		<td align="center" valign=middle sdval="29.25" sdnum="1033;0;0.00"><font color="#000000">29.25</font></td>
		<td align="center" valign=middle sdval="33.5" sdnum="1033;0;0.00"><font color="#000000">33.50</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="30.23" sdnum="1033;0;0.00"><font color="#000000">30.23</font></td>
		<td align="center" valign=middle sdval="24" sdnum="1033;0;0.00"><font color="#000000">24.00</font></td>
		<td align="center" valign=middle sdval="27.5" sdnum="1033;0;0.00"><font color="#000000">27.50</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="33" sdnum="1033;0;0.00"><font color="#000000">33.00</font></td>
		<td align="center" valign=middle sdval="29.25" sdnum="1033;0;0.00"><font color="#000000">29.25</font></td>
		<td align="center" valign=middle sdval="28.7" sdnum="1033;0;0.00"><font color="#000000">28.70</font></td>
	</tr>
	<tr>
		<td height="21" align="center" valign=middle><b><font color="#000000">Falcon-7B</font></b></td>
		<td align="center" valign=middle sdval="26.25" sdnum="1033;0;0.00"><font color="#000000">26.25</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="29.38" sdnum="1033;0;0.00"><font color="#000000">29.38</font></td>
		<td align="center" valign=middle sdval="31" sdnum="1033;0;0.00"><font color="#000000">31.00</font></td>
		<td align="center" valign=middle sdval="28.58" sdnum="1033;0;0.00"><font color="#000000">28.58</font></td>
		<td align="center" valign=middle sdval="27.25" sdnum="1033;0;0.00"><font color="#000000">27.25</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="27.75" sdnum="1033;0;0.00"><font color="#000000">27.75</font></td>
		<td align="center" valign=middle sdval="29.75" sdnum="1033;0;0.00"><font color="#000000">29.75</font></td>
		<td align="center" valign=middle sdval="28.5" sdnum="1033;0;0.00"><font color="#000000">28.50</font></td>
		<td align="center" valign=middle sdval="28.2" sdnum="1033;0;0.00"><font color="#000000">28.20</font></td>
	</tr>
</table>

## Citation
If you find our work useful, please cite our paper:
```
@article{shen2023roleeval,
      title={RoleEval: A Bilingual Role Evaluation Benchmark for Large Language Models}, 
      author={Tianhao Shen and Sun Li and Deyi Xiong},
      year={2023},
      eprint={2312.16132},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```