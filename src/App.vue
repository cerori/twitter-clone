<template>
  <div class="flex h-screen">
    <!-- 왼쪽ㄹ -->
    <div class="w-1/4 mt-5 ml-10 flex flex-col justify-between">
      <div>
        <!-- twitter logo -->
        <i class="fab fa-twitter text-2xl text-primary ml-4"></i>
        <!-- sidemenu -->
        <div class="flex flex-col items-start space-y-1">
          <!-- sidemenu items -->
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-home fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">홈</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-hashtag fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">탐색하기</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-bell fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">알림</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-envelope fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">쪽지</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-bookmark fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">북마크</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-list-alt fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">리스트</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-user fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">프로필</span>
          </div>
          <div
            class="hover:text-primary hover:bg-lighter px-4 py-2 rounded-full"
          >
            <i class="fas fa-ellipsis-h fa-fw text-2xl"></i>
            <span class="ml-5 text-lg">더보기</span>
          </div>
        </div>
        <!-- tweet button -->
        <div class="mr-3">
          <button
            class="
              mt-3
              bg-primary
              text-white
              w-full
              h-12
              rounded-full
              hover:bg-dark
            "
          >
            Tweet
          </button>
        </div>
      </div>
      <!-- profile button -->
      <div class="mr-3 mb-3">
        <button
          class="
            mt-3
            px-2
            py-1
            w-full
            h-12
            rounded-full
            hover:bg-blue-50
            flex
            items-center
          "
        >
          <img src="http://picsum.photos/100" class="w-10 h-10 rounded-full" />
          <div class="ml-2">
            <div class="text-sm font-bold">lgsoft.co.kr</div>
            <div class="text-xs text-gray-500 text-left">lgsoft.co.kr</div>
          </div>
          <i class="ml-auto fas fa-ellipsis-h fa-fw text-xs"></i>
        </button>
      </div>
    </div>
    <!-- 오른쪽 -->
    <div class="flex-1 bg-red-200"></div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
