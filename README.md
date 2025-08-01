# majubom
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>마주봄 - 30대 만남 주선</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            /* Softer, more inviting gradient background */
            background: linear-gradient(to bottom right, #f8f9fa, #e9ecef); /* Very light gray to slightly darker light gray */
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 1.5rem; /* Increased padding for better spacing */
        }
        /* Main content wrapper for a clean, professional look */
        .main-content-wrapper {
            background-color: #ffffff;
            padding: 2.5rem 3.5rem; /* More generous padding */
            border-radius: 1.5rem; /* Consistent rounded corners */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.08), 0 5px 15px rgba(0, 0, 0, 0.05); /* Refined shadow for depth */
            max-width: 36rem; /* Slightly wider for better readability */
            width: 100%;
            text-align: center;
            border: 1px solid #e0e0e0; /* Subtle border for definition */
        }
        @media (min-width: 768px) {
            .main-content-wrapper {
                padding: 3.5rem 4.5rem;
            }
        }
        /* Custom styles for buttons to make them more inviting */
        .btn-primary {
            background-color: #4c6ef5; /* A more professional blue */
            color: white;
            font-weight: 600;
            padding: 0.875rem 2.5rem;
            border-radius: 9999px; /* Fully rounded */
            box-shadow: 0 4px 10px rgba(76, 110, 245, 0.3);
            transition: all 0.3s ease-in-out;
        }
        .btn-primary:hover {
            background-color: #364fc7; /* Darker blue on hover */
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(76, 110, 245, 0.4);
        }
        .btn-secondary {
            background-color: #fcc419; /* A softer, more inviting yellow */
            color: #343a40; /* Darker text for contrast */
            font-weight: 600;
            padding: 0.875rem 2.5rem;
            border-radius: 9999px;
            box-shadow: 0 4px 10px rgba(252, 196, 25, 0.3);
            transition: all 0.3s ease-in-out;
        }
        .btn-secondary:hover {
            background-color: #f0b300; /* Darker yellow on hover */
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(252, 196, 25, 0.4);
        }
        /* Section backgrounds for better visual separation */
        .section-bg-light-blue {
            background-color: #e3f2fd; /* Very light blue */
        }
        .section-bg-light-green {
            background-color: #e8f5e9; /* Very light green */
        }
    </style>
</head>
<body>
    <div class="main-content-wrapper">
        <!-- Header Section -->
        <header class="mb-10">
            <h1 class="text-5xl font-extrabold text-gray-900 mb-4">
                <span class="text-blue-700">마주봄</span>
            </h1>
            <p class="text-xl text-gray-700 leading-relaxed">
                30대, 진정성 있는 인연을 찾는 당신을 위한 프리미엄 만남 주선 서비스
            </p>
        </header>

        <!-- Main Content Section -->
        <main>
            <!-- How Majubom Works / Pricing Section -->
            <section class="mb-10 section-bg-light-blue p-8 rounded-2xl">
                <h2 class="text-3xl font-bold text-blue-800 mb-6">마주봄, 이렇게 특별합니다</h2>
                <div class="text-lg text-gray-800 leading-relaxed">
                    <p class="mb-4">
                        마주봄은 당신의 소중한 인연을 위해 **투명하고 합리적인 시스템**을 제공합니다.
                    </p>
                    <p class="mb-2">
                        ✔️ <strong>가입비: <span class="text-blue-600 font-bold">완전 무료</span></strong>
                    </p>
                    <p class="mb-5">
                        ✔️ <strong>매칭 성공 사례비: <span class="text-blue-600 font-bold">단 3만원</span></strong>
                    </p>
                    <p class="mb-2 font-semibold">
                        **매칭 성공 기준:**
                    </p>
                    <p class="text-base text-gray-700">
                        서로의 개인정보와 사진을 신중하게 확인한 후, <br class="md:hidden">실제로 첫 만남이 성사되면 성공으로 간주합니다.
                    </p>
                </div>
            </section>

            <!-- Participation Application Section -->
            <section class="mb-10">
                <h2 class="text-3xl font-bold text-gray-800 mb-6">새로운 인연, 지금 시작하세요</h2>
                <p class="text-lg text-gray-700 mb-8">
                    마주봄을 통해 당신의 이상형을 만나고 싶으시다면, <br class="md:hidden">아래 버튼을 눌러 안전하게 신청해주세요.
                </p>
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdFdAvYoz6w_Hdyn3Wp1YNZUYvv4o2GmuAbGuLM5u8dsqpkpA/viewform?usp=header"
                   target="_blank"
                   rel="noopener noreferrer"
                   class="inline-block btn-primary">
                    참가 신청하기
                </a>
            </section>

            <!-- Success Stories Section -->
            <section class="mb-10 section-bg-light-green p-8 rounded-2xl">
                <h2 class="text-3xl font-bold text-green-800 mb-6">마주봄이 만들어낸 행복한 이야기들</h2>
                <div class="text-lg text-gray-800 leading-relaxed text-left">
                    <div class="mb-6 pb-6 border-b border-green-300 last:border-b-0">
                        <p class="font-semibold text-green-700 text-xl mb-1">"정말 꿈같은 만남이었어요!" - 김OO님 (34세)</p>
                        <p class="text-base mt-1">
                            오랜만에 진지한 만남을 찾고 있었는데, 마주봄 덕분에 저와 정말 잘 맞는 분을 만났습니다. 꼼꼼한 매칭 과정과 진심 어린 조언 덕분에 좋은 인연을 찾을 수 있었어요. 감사드립니다!
                        </p>
                    </div>
                    <div class="mb-6 pb-6 border-b border-green-300 last:border-b-0">
                        <p class="font-semibold text-green-700 text-xl mb-1">"새로운 시작을 선물해준 마주봄" - 박OO님 (36세)</p>
                        <p class="text-base mt-1">
                            바쁜 일상 속에서 새로운 사람을 만날 기회가 없었는데, 마주봄이 저에게 딱 맞는 분을 소개해 주셨어요. 서로의 가치관과 취미가 비슷해서 대화가 끊이지 않았고, 지금은 행복한 연애를 이어가고 있습니다.
                        </p>
                    </div>
                     <div class="mb-6 pb-6 border-b border-green-300 last:border-b-0">
                        <p class="font-semibold text-green-700 text-xl mb-1">"편안하고 신뢰 가는 서비스" - 이OO님 (32세)</p>
                        <p class="text-base mt-1">
                            개인 정보 확인부터 만남 성사까지 모든 과정이 투명하고 신뢰가 갔습니다. 특히, 사진 확인 절차가 있어서 안심하고 만남에 나설 수 있었어요. 덕분에 좋은 분과 즐거운 시간을 보냈습니다.
                        </p>
                    </div>
                </div>
            </section>

            <!-- Inquiry and Consultation Section -->
            <section>
                <h2 class="text-3xl font-bold text-gray-800 mb-6">궁금한 점이 있으신가요?</h2>
                <p class="text-lg text-gray-700 mb-8">
                    마주봄에 대해 더 알고 싶거나 상담이 필요하시면, <br class="md:hidden">아래 카카오톡 오픈채팅으로 편하게 문의해주세요.
                </p>
                <a href="https://open.kakao.com/o/sgLs9M1b"
                   target="_blank"
                   rel="noopener noreferrer"
                   class="inline-block btn-secondary">
                    카카오톡 상담하기
                </a>
            </section>
        </main>

        <!-- Footer Section -->
        <footer class="mt-12 text-gray-600 text-sm">
            <p>&copy; 2025 마주봄. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
