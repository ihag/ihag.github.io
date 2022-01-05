---
layout: main
main: true
title: IHAG
---

<div class="loading-animation">
    <div class="about">
        <div class="section">
            <div class="title index">01</div>
            <div class="content">
                <h1 class="subtitle">학력</h1>
                <ul class="culture">
                    <li>2014.02 | 제주외국어고등학교 졸업</li>
                    <li>2017.02 | 제주대 컴퓨터공학과 중퇴</li>
                    <li>2021.08 | 한양대 화학공학과 졸업</li>
                </ul>
            </div>
        </div>
        <div class="section">
            <div class="title index">02</div>
            <div class="content">
                <h1 class="subtitle">개발</h1>
                <ul class="environment">
                    <li>Python</li>
                    <li>Html Css JavaScript</li>
                </ul>
            </div>
        </div>
        <!--<div class="section">
            <div class="title index">03</div>
            <div class="content">
                <h1 class="subtitle">개발자 소개</h1>
                <div class="divider"></div>
                <div class="group">
                    <div class="group-name">#리더 #대장 #소원수리</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'leader' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
                <div class="group">
                    <div class="group-name">#백엔드 #인프라 #웹</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'backend' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
                <div class="group">
                    <div class="group-name">#데이터 #DBA</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'data' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
                <div class="group">
                    <div class="group-name">#프론트엔드 #웹</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'frontend' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
                <div class="group">
                    <div class="group-name">#퍼블리셔</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'publisher' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
                <div class="group">
                    <div class="group-name">#앱 #Android #iOS</div>
                    <ul class="member">
                        {% assign members = site.data.members | where: 'group', 'app' | where_exp: 'member', 'member.drop != true' | sort: 'id' %}
                        {% for member in members %}
                            {% include about-member.html %}
                        {% endfor %}
                    </ul>
                </div>
            </div>
        </div>-->
    </div>
</div>
