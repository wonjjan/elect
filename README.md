<h1>전기료 계산기(주택용만 가능)</h1>

<form method="post">
    {% csrf_token %}
    <a>현재 전기 사용량</a>
    <input name="now_elect"><br><br> 
    <button>입력 완료</button>
</form>

{% if ee %}
    <a>현재 사용량 : {{ ne }}</a><br><br>
    <a>현재 전기료 : {{ ee }}</a><br><br>
    </form>
{% endif %}
