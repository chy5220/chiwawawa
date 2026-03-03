<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>林さんの☆Happyガチャ</title>
    <style>
        :root {
            --primary-pink: #ffafbd;
            --secondary-pink: #ffc3a0;
            --rarity-r: #a1c4fd;
            --rarity-sr: #f9d423;
            --rarity-ssr: #ff0080;
        }

        body {
            background: linear-gradient(135deg, #fff5f8 0%, #e0f2fe 100%);
            font-family: 'Helvetica Neue', Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }

        /* メインコンテナ */
        .game-container {
            background: white;
            width: 90%;
            max-width: 400px;
            height: 600px;
            border-radius: 30px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.1);
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            padding: 20px;
            border: 8px solid #fff;
        }

        h1 {
            color: #ff7eb3;
            font-size: 24px;
            text-shadow: 2px 2px 0px #fff;
        }

        /* ガチャ台の見た目 */
        .gacha-machine {
            width: 200px;
            height: 250px;
            background: var(--primary-pink);
            border-radius: 50% 50% 20% 20%;
            position: relative;
            border: 5px solid #ff85a1;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .gacha-inside {
            width: 150px;
            height: 150px;
            background: rgba(255,255,255,0.3);
            border-radius: 50%;
            display: flex;
            flex-wrap: wrap;
            padding: 10px;
            justify-content: center;
        }

        .capsule-deco {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            margin: 2px;
            animation: bounce 2s infinite ease-in-out;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform:
